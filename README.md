# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

Another challenge to enhance coding speed.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

## My process

- This card layout is similar to the the previous challenges so a similar markup was used and similar box model or flexbox techniques employed.
- Contruct the mobile version first.

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SASS

### What I learned

- Study both mobile and desktop designs before jumping into the code. The desktop template has a reversed order requiring more consideration of the initial layout (more strategic use of parent containers) or more complex css tricks to resolve. Because the mobile version was only studied in detail initially, this feature was overlooked and some time was lost trying to implement changes when the desktop template was then studied in detail. In the end, additional divs were used and further flexbox properties implemented.
- Still, considerable time was used getting the card postioning in place in the desktop version. One particular problem was getting the banner image to fit its container, which in itself was a child container to a parent wrapper. In the end, margins and paddings for all neighbouring elements had to be readjusted in a trial and error scenario.
- Overall, this challenge still took about the same time as the previous which is disappointing (typical turnaround has been 2.5 -> 3hrs) but admittedly each subsequent challenge has added another layer of complexity.

### Continued development

Study all designs first!

### Useful resources

- Wasn't aware of applying linear gradient background colour to a background image. When declaring background-image, before the URL(), prepend: linear gradient(first colour, second colour), url(); if both colours are identical, this can work as the background-color opacity effect.

## Author

wkan17012021

## Acknowledgments

https://stackoverflow.com/questions/7241341/can-i-set-an-opacity-only-to-the-background-image-of-a-div
