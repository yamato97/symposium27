---
title: Home
---

# **Biomolecular Interactions and Reactions:** <br> **Theory and Experiments**

{% include figure.html img="eye-catch-sample.png" alt="intro image here" caption="Symposium '27" width="75%" %}

### **DATE: Saturday, January 30, 2027**

### **PLACE: Neorex place seminar room, Science South Bldg., Nagoya Univ.**

<!-- A minimal Jekyll theme for creating workshop websites.

*Add your workshop abstract here!* -->

*Biomolecular interactions are key factors governing biological functions. For this symposium, we have invited leading theoretical and experimental researchers to present the latest advances in their research, which makes full use of computational methods, nuclear magnetic resonance (NMR), and biochemical experiments.*

| **INVITED SPEAKERS** |      |  
| :--------------- | :---- |  
|**Hidekazu HIROAKI** |**Nagoya**|  
|**David LEITNER** |**Nevada** |  
|**Toshifumi MORI** |**Kyoto** |  
|**Chihiro SATO** | **Nagoya**|  
|**Norio YOSHIDA** | **Nagoya** |  
|**Futa YOSHIMURA** | **Nagoya** |  

<!-- Learn how to create a super quick easy website for a workshop by writing a few markdown files! 
Host it for free on GitHub with gh-pages, and share!
Fun! -->

<!-- *See also:* [workshop-template-b](https://evanwill.github.io/workshop-template-b/), Bootstrap version. -->

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by [Computational Biophysics Lab, Nagoya University](https://www.comp-biophys.com/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
