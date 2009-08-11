=== Plugin Name ===
Contributors: jolley_small
Donate link: http://blue-anvil.com/archives/wordpress-sidebar-login-2-optimised-for-wordpress-26
Tags: login, sidebar, widget, sidebar login, meta, form, register
Requires at least: 2.5
Tested up to: 2.8
Stable tag: 2.2.6

Adds a sidebar widget to let users login.

== Description ==

Sidebar-Login has both a widget and a template tag to allow you to have a login form in the sidebar of your wordpress powered blog.

It lets users login, and then redirects them back to the page they logged in from rather than the backend, it also shows error messages.

You can configure the plugin in <code>Admin > Tools > Sidebar Login</code> after installing it.

= Localization Files =

Czech Translation - http://wordpress.blog.mantlik.cz/plugins/sblogin-cs/
Catalan Translation by Marc Vinyals
French Translation by Andy
Estonian Translation by Marko Punnar
Dutch Translation by Ruben Janssen
German Translation by GhostLyrics
Italian Translation by Alessandro Spadavecchia
Hungarian translation by Laszlo Dvornik
Hungarian (2) translation by Balint Vereskuti
Russian translation by Fat Cow (http://www.fatcow.com)
Romanian translation by Victor Osorhan
Spanish translation by Tribak (http://blog.tribak.org/sidebar-login-es_es/)
Spanish (2) translation by Ricardo Vilella (http://www.ifconfig.com.ar/general/traduccion-al-espanol-del-plugin-sidebar-login-para-wordpress/)
Danish translation by Per Bovbjerg
Portuguese translation by Alvaro Becker
Polish translation by merito
Polish (2) translation by Darek Wapinski
Icelandic translation by Hákon Ásgeirsson
Arabic translation by khalid

Note: Those with more than one translation are found in langs/alternate/. To use the alternatives move them from /alternate/ into /langs/.

== Installation ==

= First time installation instructions =

   1. Unzip and upload the php file to your wordpress plugin directory
   2. Activate the plugin
   3. For a sidebar widget: Goto the design > widgets tab - Drag the widget into a sidebar and save!
   4. To use the template tag: Add &lt;?php sidebarlogin(); ?&gt; to your template.
   
= Configuration =

You will find a config page in tools/settings > Sidebar Login. Here you can set links and redirects up.

== Screenshots ==

1. Login Form
2. After Login

== Changelog ==

= 2.2.6 =
*	Added changelog to readme.
*	OpenID Plugin (http://wordpress.org/extend/plugins/openid/) Integration.
*	%username% can be used in your custom links shown when logged in (gets replaced with username)
*	WP-FacebookConnect (http://wordpress.org/extend/plugins/wp-facebookconnect/) integration (untested!)
*	Minor fixes (worked through a big list of em!)
