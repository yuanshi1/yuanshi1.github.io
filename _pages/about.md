---
permalink: /
title: "Hello!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third year PhD student at MIT Operations Research Center, co-advised by Prof. Karen Zheng and Prof. Joann de Zegher. 

My research interests lie broadly in the areas of optimization and incentive design for social good, with applications in healthcare and sustainability. My current research agenda focuses on developing analytics tools and game theoretic models for improving livelihood and promoting sustainability in smallholder supply chains. 

Research
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

