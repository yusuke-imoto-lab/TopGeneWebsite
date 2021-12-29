---
permalink: /docs/installation/
sidemenu: true
description: "Installation instructions."
modified: 2021-12-29
tags: [manual]
---

<div class= "container">
  <div class= "row">
    <div class= "col-sm-4">
      <!--  <nav id= "toc" data-spy= "affix" data-toggle= "toc"></nav>-->
      <ul class="section-nav" id= "toc" data-spy= "affix" data-toggle= "toc">
        <li class="toc-entry toc-h2"><a href="{{ site.baseurl }}/docs/introduction">Introduction</a></li>
        <li class="toc-entry toc-h2"><a class="active" href="{{ site.baseurl }}/docs/installation">Installation</a>
          <ul>
            <li class="toc-entry toc-h3"><a href="#required-software">Required software</a></li>
          </ul>
        </li>
        <li class="toc-entry toc-h2"><a href="{{ site.baseurl }}/docs/help">Getting help</a></li>
      </ul>
    </div>
    <!-- main content area -->
    <div class= "col-sm-8">
      <nav aria-label="breadcrumb">
        <ol class="breadcrumb">
          <li class="breadcrumb-item"><a href="{{ site.baseurl }}/">Home</a></li>
          <li class="breadcrumb-item"><a href="{{ site.baseurl }}/docs/introduction">Docs</a></li>
          <li class="breadcrumb-item active" aria-current="page">Installation</li>
        </ol>
      </nav>

<div markdown="1">

## Installation
To install scRECODE package, use `pip` as follows:

```bash
$ pip install screcode
```

To use scRECODE, `import screcode`.

```python
import screcode
```

### Required software
<a name="required-software"></a>
* Python3
* numpy
* scipy
* scikit-learn

</div>

  </div>
</div>
