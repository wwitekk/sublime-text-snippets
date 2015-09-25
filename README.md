# Sublime Text snippets
Sublime Text Snippets for Busiess Catalyst (Liquid) and general.

##Table of content:
- [Installation](https://github.com/wwitekk/sublime-text-snippets#installation)
- [safe image](https://github.com/wwitekk/sublime-text-snippets#safe-image)
- [safe tag](https://github.com/wwitekk/sublime-text-snippets#safe-tag)
- [short webb app module](https://github.com/wwitekk/sublime-text-snippets#short-webb-app)
- [if](https://github.com/wwitekk/sublime-text-snippets#if)
- [if - else](https://github.com/wwitekk/sublime-text-snippets#if-else)
- [if - elseif - else](https://github.com/wwitekk/sublime-text-snippets#if-elseif-else)
- [for](https://github.com/wwitekk/sublime-text-snippets#for)
- other([image placeholder](https://github.com/wwitekk/sublime-text-snippets#image-placeholder); 
 [console log](https://github.com/wwitekk/sublime-text-snippets#console-log))

##Installation:
Place *.sublime-snippet files into folder: "c:\Users\[user name]\AppData\Roaming\Sublime Text 3\Packages\User\" 

##Snippets:

###Safe image
file: bc-liquid-safe-image.sublime-snippet
snippet: liqsafeimg
documentation: [link](http://docs.businesscatalyst.com/dev-assets/reference#!/module-reference/web-apps/index.html)

Hides broken images and alt tags if no image (e.g. no added in webapp) or 'src' attribute incorrect 

###Safe tag
file: bc-liquid-safe-tag.sublime-snippet

snippet: liqsafetag

Hides block of html code if (e.g. webapp) tag empty or null

###Short webb app
file: bc-liquid-webapp.sublime-snippet

snippet: webapp

Renders module_webbapp with only basic attributes

###if
file: bc-liquid-if.sublime-snippet

snippet: liqif

documentation: [link](http://docs.businesscatalyst.com/dev-assets/reference#!/liquid-reference/reference/logic-tags.html!if)

Just *if* structure

###if-else
file: bc-liquid-else.sublime-snippet

snippet: liqelse

documentation: [link](http://docs.businesscatalyst.com/dev-assets/reference#!/liquid-reference/reference/logic-tags.html!if-else)

Just *if-else* structure

###if-elseif-else
file: bc-liquid-elseif.sublime-snippet

snippet: liqelseif

documentation: [link](http://docs.businesscatalyst.com/dev-assets/reference#!/liquid-reference/reference/logic-tags.html!if-else)

Just *if elseif else* structure

###for
file: bc-liquid-for.sublime-snippet

snippet: liqfor

documentation: [link](http://docs.businesscatalyst.com/dev-assets/reference#!/liquid-reference/reference/logic-tags.html!for)

Just *for* loop structure



###Image placeholder
file: image-placeholder.sublime-snippet

snippet: placeit

Renders placeholder image. Using: [https://placehold.it]()

###Console log
file: console-log.sublime-snippet

snippet: co

Shortcut for js console.log();
