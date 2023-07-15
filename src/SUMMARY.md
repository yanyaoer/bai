# Summary

> 满语“长白”,意为“永远的白”。相传长白山峰顶终年积雪不化,亘古长白,冰雪覆盖,所以人们称它为“长白山”

---

- [长白](bai.md)


HTML renderer options

```toml
# Example book.toml file with all output options.
[book]
title = "Example book"
authors = ["John Doe", "Jane Doe"]
description = "The example book covers examples."

[output.html]
theme = "my-theme"
default-theme = "light"
preferred-dark-theme = "navy"
curly-quotes = true
mathjax-support = false
copy-fonts = true
additional-css = ["custom.css", "custom2.css"]
additional-js = ["custom.js"]
no-section-label = false
git-repository-url = "https://github.com/rust-lang/mdBook"
git-repository-icon = "fa-github"
edit-url-template = "https://github.com/rust-lang/mdBook/edit/master/guide/{path}"
site-url = "/example-book/"
cname = "myproject.rs"
input-404 = "not-found.md"
```
