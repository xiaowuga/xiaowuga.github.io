---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! My name is Jing-En Jiang (江敬恩). I am a fourth-year Ph.D. student in Computer Science at Shandong University (SDU), advised by [Prof. Changhe Tu](https://faculty.sdu.edu.cn/tuzhanghe/en/index.htm).

My research focuses on 3D generative models, 3D agents, and CAD-related problems.

Outside of work, I enjoy speedcubing and can solve a 3×3 Rubik's Cube in under 20 seconds.

# 🔥 News
- *2026.10*: &nbsp;🎉🎉 I joined Bambu Lab as a research intern.
- *2025.03*: &nbsp;🎉🎉 One paper got accepted by ACM Transactions on Graphics (SIGGRAPH 2025).

# 💻 Internships
- <img src='images/logos/bambulab.svg' alt='Bambu Lab' style='height:1.3em; vertical-align:middle'> *2026.10 - now*, **Research Intern**, Bambu Lab, working on 3D agents with [Buyu Li](https://libuyu.github.io/).
- <img src='images/logos/v2fun.png' alt='v2fun' style='height:1.3em; vertical-align:middle'> *2026.07 - 2026.10*, **Research Intern**, v2fun, working on 3D generative models with Xibin Song and Senbo Wang.

# 📝 Selected Publications

<sup>*</sup> Equal contribution, <sup>$\dagger$</sup> Corresponding author


<div class='paper-box'><div class='paper-box-image'><div><img src='images/DeFillet2.jpg' alt="DeFillet" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**DeFillet: Detection and Removal of Fillet Regions in Polygonal CAD Models**](https://raw.githubusercontent.com/xiaowuga/xiaowuga.github.io/main/pub/static/pdf/Defillet_Sig_2025.pdf)

**ACM Transactions on Graphics (SIGGRAPH 2025), CCF-A**

**Jing-En Jiang**, Hanxiao Wang, Mingyang Zhao, Dong-Ming Yan, Shuangmin Chen, Shiqing Xin, Changhe Tu, Wenping Wang

[**Project**](https://xiaowuga.github.io/pub/DeFillet.html) \| [**Video**](https://www.bilibili.com/video/BV1aCtMzPEXe/) \| [**Code**](https://github.com/xiaowuga/DeFillet) \| [**EXE(Win)**](https://github.com/xiaowuga/DeFillet/releases/tag/v1.0)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><img src='images/CVPR24.png' alt="Correspondence-Free Non-Rigid Point Set Registration" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Correspondence-Free Non-Rigid Point Set Registration Using Unsupervised Clustering Analysis**](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhao_Correspondence-Free_Non-Rigid_Point_Set_Registration_Using_Unsupervised_Clustering_Analysis_CVPR_2024_paper.pdf) 

**IEEE CVPR 2024, <span style="color:red">Highlight</span>, CCF-A**

Mingyang Zhao, **Jing-En Jiang**, Lei Ma, Shiqing Xin, Gaofeng Meng, Dong-Ming Yan

[**Project**](https://zikai1.github.io/pub/CluReg/index.html) \| [**Code**](https://github.com/zikai1/CVPR24_PointSetReg) \| [**Poster**](https://zikai1.github.io/slides/CVPR24_Creg_poster.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/PrimFit.png' alt="PrimFit" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Structure-Aware Surface Reconstruction via Primitive Assembly**](https://openaccess.thecvf.com/content/ICCV2023/papers/Jiang_Structure-Aware_Surface_Reconstruction_via_Primitive_Assembly_ICCV_2023_paper.pdf)

**IEEE ICCV 2023, CCF-A**

**Jing-En Jiang<sup>*</sup>**, Mingyang Zhao<sup>*</sup>, Shiqing Xin, Yanchao Yang, Hanxiao Wang, Xiaohong Jia, Dong-Ming Yan<sup>$\dagger$</sup>

[**Video**](https://www.youtube.com/watch?v=a5w2-0mOcS0) \| [**Code**](https://github.com/xiaowuga/PrimFit) \| [**EXE(Win)**](https://github.com/xiaowuga/PrimFit/releases) \| [**Poster**](https://xiaowuga.github.io/slides/ICCV2023_PrimFit_poster_v3.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/EDSF.jpg' alt="EDSF" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**EDSF: Fast and Accurate Ellipse Detection via Disjoint-set Forest**](https://ieeexplore.ieee.org/document/9859889)

**IEEE ICME 2022, CCF-B**

**Jing-En Jiang<sup>*</sup>**, Mingyang Zhao<sup>*</sup>, Zeyu Shen, Dong-Ming Yan<sup>$\dagger$</sup>

[**Code**](https://github.com/xiaowuga/EDSF) \| [**Slide**](https://xiaowuga.github.io/slides/EDSF_ICME_2022_v4.pptx)

</div>
</div>

# 📖 Education
- <img src='images/logos/sdu.png' alt='Shandong University' style='height:1.3em; vertical-align:middle'> *2023.09 - now*, **Ph.D. in Computer Technology**, Shandong University, Qingdao, Shandong, China, advised by [Prof. Changhe Tu](https://faculty.sdu.edu.cn/tuzhanghe/en/index.htm).
- <img src='images/logos/ucas.png' alt='University of Chinese Academy of Sciences' style='height:1.3em; vertical-align:middle'> *2020.09 - 2023.06*, **M.Eng. in Electronic and Information Engineering**, University of Chinese Academy of Sciences, Beijing, China, advised by [Prof. Dong-Ming Yan](https://sites.google.com/site/yandongming/).
- <img src='images/logos/tiangong.png' alt='Tiangong University' style='height:1.3em; vertical-align:middle'> *2016.09 - 2020.06*, **B.Eng. in Software Engineering**, Tiangong University, Tianjin, China


# 🎖 Honors and Awards
- *2025* **Dean's Scholarship** and **First-Class Academic Scholarship**, School of Computer Science and Technology, Shandong University
- *2022* **Merit Student**, University of Chinese Academy of Sciences
- <img src='images/logos/icpc.png' alt='ICPC' style='height:1.3em; vertical-align:middle'> *2018.12* [**Silver Medal**](https://icpc.global/ICPCID/9TIGI8D06O3U), ACM/ICPC Asia-East Continent Final
- <img src='images/logos/ccpc.png' alt='CCPC' style='height:1.3em; vertical-align:middle'> *2018.09* [**Silver Medal**](https://ccpc.io/post/135), China Collegiate Programming Contest


