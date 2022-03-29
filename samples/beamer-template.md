---
marp: true
theme: beamer
paginate: true
size: 4:3
header: This is a header
footer: This is a footer
title: Marp custom themes
---
<!-- _class: title -->

# A very long title of my beamer presentation
<br/>

Author's name
University of XYZ
2022-26-03
(Only normal text will is centered now)

---

# A normal slide

# H1 again
## H2
### H3
- bullet
> quote
```
code
```
text

---
# Title page ad hoc fix

- If the title of your presentation is too long and the border intersects with the text underneath, use

```html
# Title
<br/>
<!-- empty line here --->
Author's name
University of XYZ
...
```
- make sure to leave an empty line below the `<br/>` tag