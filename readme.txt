=== Virtual Keyboard ===
Contributors: phpaid, grx3 
Donate link: http://phpaid.org/

For all text inputs on the pages you will get a keyboard so you can click instead of using the keyboard.

This was built using javascript from and I added all the nessacary compontents to work
with any wordpress installation.

== Installation ==

Easy

1. Upload `virtualkeyboard/` to the '/' of your server
2. Open virtualkeyboard.php in editor, change $keyboard_image = 'your/domain'; to your domain where the image is. Save and Close.
3. add include('virtualkeyboard.php'); virtualkeyboard_head(); to your header file if applicable, otherwise inside the <head></head> tags will do.
4. add virtualkeyboard_footer();before the </body> tag

Now browse, the javascript on the client-side takes care of the rest attaching  a keyboard to all text inputs.

== Frequently Asked Questions ==

=Can I make it select certain inputs only =

Not in the version, but possibly soon.

== Changelog ==


= 1.0 =
* First Release
