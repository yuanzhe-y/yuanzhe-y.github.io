---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

(Click [here](/yuanzhe-y.github.io/files/YangCV.pdf) to download a more detailed CV.)

Education
======
* M.A. in Philosophy, Peking University, 2026 (expected)
  * Supervisor: Yanjing Wang
* B.A. in Philosophy, Peking University, 2023
  * Supervisor: Yanjing Wang

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
