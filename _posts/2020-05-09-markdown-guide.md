---
layout: post
title: "All Markdown Syntax Supported"
subtitle: "This post contains all markdown syntax supported. You can view the rendered effect of them."
date: 2020-05-09 21:45:13 +0800
---

This is a demo of all styled elements in Jekyll Now. 

[View the markdown used to create this post](https://raw.githubusercontent.com/barryclark/www.jekyllnow.com/gh-pages/_posts/2014-6-19-Markdown-Style-Guide.md).

This is a paragraph, it's surrounded by whitespace.
Next up are some headers, they're heavily influenced by GitHub's markdown style.

## Header 2 (H1 is reserved for post titles)##

### Header 3

#### Header 4
 
A link to [Jekyll Now](http://github.com/barryclark/jekyll-now/). A big ass literal link <http://github.com/barryclark/jekyll-now/>
  
[Link to another post](/ruoji{% post_url 2020-05-08-markdown-yeah %})

An image, located within `/assets/img/team/`

![an image alt text]({{ site.baseurl }}/assets/img/team/500x500.jpg "an image title")

* A bulletted list
- alternative syntax 1
+ alternative syntax 2
  - an indented list item

1. An
2. ordered
3. list

Inline markup styles: 

- _italics_
- **bold**
- `code()` 
 
> Blockquote
>> Nested Blockquote 
 
To create code blocks, indent every line of the block by at least four spaces or one tab.

```html
    <html>
      <head>
      </head>
    </html>
```

Syntax highlighting can be used by wrapping your code in a liquid tag like so:

```javascript
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
```
or

{{ "{% highlight javascript " }}%}  
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{{ "{% endhighlight " }}%}  

 
Use two trailing spaces  
on the right  
to create linebreak tags  
 
Finally, horizontal lines
 
----
****