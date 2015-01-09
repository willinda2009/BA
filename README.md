# Tableau Animation
Animates Tableau Dashboards on the web using Tableau Server and some basic Javascript (JQuery)

# Examples

<a target="_blank" href="http://ps-data.github.io/tableau-animation/map.html">http://ps-data.github.io/tableau-animation/map.html</a>

# Implementation

In this post I will show you how to animate your Tableau dashboards on the web. This will require basic understanding of Tableau and some basic HTML and Javascript knowledge will help.

# Background
Forever Tableau dashboard developers have wanted to show how things change over time in their views. In Tableau desktop this is possible using the Pages shelf and clicking the ‘play’ button. The problem however, is that this functionality does not work on Tableau Server nor Tableau Public...until now :)

# Prerequisites
1. Tableau workbook that can be modified by changing a filter or parameter value
2. Tableau Server or account on Tableau Public
3. Web Server to host animated viz (optional)


# Setup
1. Make sure you viz will look good when the parameter value is changed. (I’m saying parameter but it could also be just a field in your data set that is being used in your viz).
2. Publish your viz to Tableau Server or Tableau Public. It goes without saying anything on Tableau Public is viewable by anyone so be careful if you’re publishing sensitive data.
3. Copy animate.html from here [animate.html](https://github.com/ps-data/tableau-animation/blob/gh-pages/animate.html) to your web server
4. Inside animate.html add your URLs to the locations array starting at line 25  (examples included in html)
5. Publish your animate.html to a web server of your choice. You may also fork this repository and use github’s pages as a free hosting of sorts.
6. Browse to your new animated map, tweak any settings that might not be right like the time spent on each viz (setInterval parameter in animate.html)

We have lots of content for Tableau training on pluralsight.com as well as we have a series of tips and tricks on our blog found here: http://blog.pluralsight.com/tableau-server-and-desktop

Enjoy!
