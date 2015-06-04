=== idbbee ===
Contributors: dbbee
Donate link: http://www.dbbee.com/plans
Author: dbbee.com
Service URI: http://www.dbbee.com
Tags: dbbee, embed, excel, access, database, publishing
Requires at least: 3.0
Tested up to: 4.1
Stable tag: 3.0
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl.html

Turn your Excel Spreadsheet, or Access database into a powerful online database application with a few clicks. 

== Description ==
* dbBee Service - http://www.dbbee.com/
* Create free account - https://thyme.dbbee.com/register/
* Available service plans - http://www.dbbee.com/plans


dbBee is frustration-free software for simple and easy publishing, maintaining and sharing data stored in your Excel Spreadsheet or Access database. dbBee lets you create search forms, reports and administration  systems without any programming. Finally, you can embed your dbBee project into your own website with just a few clicks.

It's that easy!
 
WordPress removes certain html tags because of security reasons, among them `<iframe>` and `<script>`. idbbee shortcode is used for embedding dbBee projects to your WordPress page or post as iframe element.

== Other Notes ==
= idbbee params: =
* **src** - source of the dbBee project: `[idbbee src="//thyme.dbbee.com/u/demo/"]`;
* **width** - width in pixels or in percents: `[idbbee width="90%"] or [idbbee width="640"]`, default value:100%;
* **height** - height in pixels: `[idbbee height="800"]`, default value:600;
* **scrolling** - include scrollbars: `[idbbee scrolling="no"]`, default value:yes;
* **frameborder** - width of frame border in pixels: `[idbbee frameborder="1"]`, default value:0;
* **marginheight** - margin height: `[idbbee marginheight="5"]`, default value:0;
* **marginwidth** - width of the margin: `[idbbee marginwidth="0"]`, default value:0;
* **id** - id attribute for the idbbee: `[idbbee id="dbbeeproject"]`, default value:dbBeeIFrame;
* **name** - name attribute for the idbbee: `[idbbee name="dbbeeproject"]`, default value:dbBeeIFrame;
* **class** - class attribute for the idbbee: `[idbbee class="idbBeeClass"]`, default value:dbBeeIFrameclass;
* **style** - style attribute for the idbbee: `[idbbee style="padding:0px;"]`;

== Screenshots ==

1. [idbbee] shortcode
2. [idbbee] result

== Changelog ==
= 1.0 =
* Initial release

== Installation ==

1. install and activate the plugin on the Plugins page
2. add shortcode `[idbbee src="//thyme.dbbee.com/u/demo/" width="100%" height="500"]` to page or post content