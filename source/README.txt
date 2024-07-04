Image Slider Maker README
=========================
ImageSliderMaker.com


Using in your website
---------------------

Please first make sure you have fully extracted the contents of the zip file.
In Windows, right-click on imageslidermaker.zip and select Extract All...

To get your slider working in your web page, you must add
my-slider.css, ism-2.2.min.js and the slide images to your project
directory and paste the markup (included below) into your HTML.

The directory structure of this package:

  imageslidermaker/
    README.txt
    example.html
    ism/
      css/
        my-slider.css
      js/
        ism-2.2.min.js
      image/
        slides/
          _u/1641779039649_244590.jpg
          _u/1641779039394_174285.jpg
          _u/1641779039062_83764.jpg
          _u/1641779038941_346964.jpg
          _u/1641779038841_474761.jpg
          _u/1641779038801_81737.jpg
          _u/1641779038747_163675.jpg

For a working example, open example.html in your web browser or
follow the instructions below to integrate the slider into your
project.


Step by step instructions
-------------------------

1. Paste the following into the head of your HTML file:

<link href="http://fonts.googleapis.com/css?family=PT+Sans+Narrow" rel="stylesheet" type="text/css">
<link rel="stylesheet" href="ism/css/my-slider.css"/>
<script src="ism/js/ism-2.2.min.js"></script>


2. Paste this into the body of your HTML file (at the location where:
   you would like your slider to appear in the page):

<div class="ism-slider" data-transition_type="fade" data-radio_type="thumbnail" id="my-slider">
  <ol>
    <li>
      <img src="ism/image/slides/_u/1641779039649_244590.jpg">
      <div class="ism-caption ism-caption-0">My slide caption text</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1641779039394_174285.jpg">
      <div class="ism-caption ism-caption-0">My slide caption text</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1641779039062_83764.jpg">
      <div class="ism-caption ism-caption-0">My slide caption text</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1641779038941_346964.jpg">
      <div class="ism-caption ism-caption-0">My slide caption text</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1641779038841_474761.jpg">
      <div class="ism-caption ism-caption-0">My slide caption text</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1641779038801_81737.jpg">
      <div class="ism-caption ism-caption-0">My slide caption text</div>
    </li>
    <li>
      <img src="ism/image/slides/_u/1641779038747_163675.jpg">
    </li>
  </ol>
</div>
<p class="ism-badge" id="my-slider-ism-badge"><a class="ism-link" href="http://imageslidermaker.com" rel="nofollow">generated with ISM</a></p>


3. Copy the ism/ directory into the root directory of your project.

   The css, js and image paths are relative, meaning the ism/
   directory should be in the same directory (path) as your HTML
   file containing the slider.


