=== Custom CSS for Pages/Posts/Widgets ===
Contributors: Bilal Naseer
Tags: custom css, css for pages, css for widgets, css for posts
Requires at least: 3.5
Tested up to: 4.1.1
Stable tag: 1.0

This plugin will create metabox in Pages/Posts/Widgets to add CSS which will help alot in customization.

== Description ==

This plugin can help a lot in theme customization, it will add CSS code into head section of your website but will only work for the pages/posts/widget which you will choose.



== Installation ==

1.  If you use FTP to upload your plugins, unzip the zip file and upload the resulting directoy to /wp-content/plugins/
    If you use the automatic uploader, there's no need to unzip the file first.
    
2. Activate the plugin through the 'Plugins' menu in WordPress

You will now see a new metabox on all edit screens for posts/pages/widgets.

== Screenshots ==

1. For complete demo visit http://websensepro.com/custom-css-for-pages-posts-widgets

2. For complete demo visit http://websensepro.com/custom-css-for-pages-posts-widgets

3. For complete demo visit http://websensepro.com/custom-css-for-pages-posts-widgets



== Frequently Asked Questions ==

Q: How do I enable this for my custom post types?
A: Add this line to your theme's functions.php file and change POST_TYPE to the name of your post type. 

add_post_type_support( 'POST_TYPE', 'websensepro-custom-css');

Examples: 

add_post_type_support( 'event', 'websensepro-custom-css');
add_post_type_support( 'product', 'websensepro-custom-css');

For more information, please visit the plugin's home page at:
http://websensepro.com/custom-css-for-pages-posts-widgets


== Changelog ==

= 1.0 =
• Initial release
