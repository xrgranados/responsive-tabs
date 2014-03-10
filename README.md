Responsive Tabs v1.2
====================

A simple to use, alternative, lightweight and responsive jQuery Tabs plugin.

**Demo:** http://www.cloud-eight.com/github/responsive-tabs/


Usage
=====

<ul>
  <li>Link both the responsive-tabs.css and responsive-tabs.js files into your document</li>
  <li>Place an unordered list and give it a class name 'tabs'</li>
  <li>In each list item place a hyperlink</li>
  <li>Give the hyperlinks 'href' attribute a _unique_ anchor</li>
  <li>Place a div after your unordered list with a class name 'tabs-content'</li>
  <li>Inside that div place another div with a class name 'tabs-panel'</li>
  <li>Place a 'tabs-panel' div for each of the list items using the unique 'href' as that div's 'id' attribute</li>
</ul>

Since unordered lists are hidden in smaller devices, we use another div with a class of 'tab-title' within each 'tabs-panel' to place the list items hyperlink display text<br /><br />

You can also change the position of your tabs' links by adding the class 'tabs-left' or 'tabs-right' to both the 'tabs' and 'tabs-content' elements.<br /><br />

If you wish to change the status of a panel with a hyperlink from within the panel itself, give that link a class name of 'tabs-panel-link' and set the URL to the unique 'id' of the panel you wish to display.


Browser Compatibility
=====================

<ul>
  <li>IE 8+</li>
  <li>Firefox</li>
  <li>Chrome</li>
  <li>Safari</li>
  <li>Opera</li>
  <li>Most mobile browsers</li>
</ul>


Author
======

Joe Mottershaw, Cloud Eight<br />
http://www.cloud-eight.com