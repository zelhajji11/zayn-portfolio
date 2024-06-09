---
layout: page
title: Personal Works
permalink: /personal-works/
---

# Personal Works

Welcome to my personal works section where I share my DIY projects, gardening endeavors, and photography.

## Photography
Here's a selection of my favorite shots:

<div class="your-class">
  <div><img src="{{ 'assets/images/Beach-Hawaii.jpg' | relative_url }}" alt="Beach Hawaii"></div>
  <div><img src="{{ 'assets/images/Candle-Light.jpg' | relative_url }}" alt="Candle Light"></div>
  <div><img src="{{ 'assets/images/Hiking-Angeles-Crest.jpg' | relative_url }}" alt="Hiking Angeles Crest"></div>
  <div><img src="{{ 'assets/images/Hiking-Nature-1.JPG' | relative_url }}" alt="Hiking Nature 1"></div>
  <div><img src="{{ 'assets/images/Lantern-Fest.jpg' | relative_url }}" alt="Lantern Fest"></div>
  <div><img src="{{ 'assets/images/Malibu-Beach.jpg' | relative_url }}" alt="Malibu Beach"></div>
  <div><img src="{{ 'assets/images/Sailing.jpg' | relative_url }}" alt="Sailing"></div>
  <div><img src="{{ 'assets/images/Beach-Malibu.jpg' | relative_url }}" alt="Beach Malibu"></div>
  <div><img src="{{ 'assets/images/Double-Rainbow.jpg' | relative_url }}" alt="Double Rainbow"></div>
  <div><img src="{{ 'assets/images/Hiking-Leafs.jpg' | relative_url }}" alt="Hiking Leafs"></div>
  <div><img src="{{ 'assets/images/Hiking-Nature-2.JPG' | relative_url }}" alt="Hiking Nature 2"></div>
  <div><img src="{{ 'assets/images/LA-Sunset2.jpg' | relative_url }}" alt="LA Sunset 2"></div>
  <div><img src="{{ 'assets/images/Playing-with-light.jpg' | relative_url }}" alt="Playing with Light"></div>
  <div><img src="{{ 'assets/images/Tea-House.jpg' | relative_url }}" alt="Tea House"></div>
  <div><img src="{{ 'assets/images/Bird-of-Flame.jpg' | relative_url }}" alt="Bird of Flame"></div>
  <div><img src="{{ 'assets/images/Fender.jpg' | relative_url }}" alt="Fender"></div>
  <div><img src="{{ 'assets/images/Hiking-Mnt-Lowe.jpg' | relative_url }}" alt="Hiking Mnt Lowe"></div>
  <div><img src="{{ 'assets/images/Hiking-Tree.jpg' | relative_url }}" alt="Hiking Tree"></div>
  <div><img src="{{ 'assets/images/LA-Sunset.jpg' | relative_url }}" alt="LA Sunset"></div>
  <div><img src="{{ 'assets/images/Rabat.jpg' | relative_url }}" alt="Rabat"></div>
  <div><img src="{{ 'assets/images/Zayn-Hiking.jpg' | relative_url }}" alt="Zayn Hiking"></div>
</div>

<!-- Link to jQuery -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- Link to Slick Carousel files -->
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel/slick/slick.css"/>
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel/slick/slick-theme.css"/>
<script src="https://cdn.jsdelivr.net/npm/slick-carousel/slick/slick.min.js"></script>

<script>
$(document).ready(function(){
  $('.your-class').slick({
    dots: true,
    infinite: true,
    speed: 300,
    slidesToShow: 1,
    adaptiveHeight: true
  });
});
</script>
