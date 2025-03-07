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
Hello! I am currently a PhD student (since 2023) at the AI Thrust, [HKUST(GZ)](https://www.hkust-gz.edu.cn/), under the guidance of Dr. Yingcong Chen. My research interests are in deep learning and computer vision, with a particular focus on physically based generative models. I lift weights 🏋️‍♂️ in my spare times.

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.02*: &nbsp;🎉🎉 Our Paper [Uni-Renderer: Unifying Rendering and Inverse Rendering Via Dual StreamDiffusion](https://arxiv.org/abs/2412.15050) is accepted by CVPR.
- *2025.02*: &nbsp;🎉🎉 Our Paper [TransPixeler: Advancing Text-to-Video Generation with Transparency](https://arxiv.org/abs/2501.03006) is accepted by CVPR.
- *2024.12*: &nbsp;🎉🎉 Our Paper [Uni-Renderer: Unifying Rendering and Inverse Rendering Via Dual StreamDiffusion](https://arxiv.org/abs/2412.15050) is released.
- *2024.12*: &nbsp;🎉🎉 Our paper [Motion Dreamer: Realizing Physically Coherent Video Generation through Scene-Aware Motion Reasoning](https://arxiv.org/abs/2412.00547) is released. 
- *2024.05*: &nbsp;🎉🎉 Our paper [Defect Spectrum: A Granular Look of Large-Scale Defect Datasets with Rich Semantics](https://arxiv.org/abs/2310.17316) is released. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR</div><img src='images/uni_renderer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Uni-Renderer: Unifying Rendering and Inverse Rendering Via Dual StreamDiffusion](https://arxiv.org/pdf/2412.15050)

**Zhifei Chen**$^{\star}$, Tianshuo Xu$^{\star}$, Wenhang Ge$^{\star}$, Leyi Wu, Dongyu Yan, Jing He, Luozhou Wang, Lu Zeng, Shunsi Zhang, Yingcong Chen$^{\dagger}$
* $^{\star}$Equal contribution  $^{\dagger}$Corresponding Author

[**Paper**](https://arxiv.org/pdf/2412.15050) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Github**](https://github.com/EnVision-Research/Uni-Renderer) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV</div><img src='images/defect_spectrum_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Defect Spectrum: A Granular Look of Large-Scale Defect Datasets with Rich Semantics](https://arxiv.org/abs/2310.17316)

Shuai Yang$^{\star}$, **ZhiFei Chen**$^{\star}$, Pengguang Chen, Xi Fang, Yixun Liang, Shu Liu, Yingcong Chen$^{\dagger}$
* $^{\star}$Equal contribution  $^{\dagger}$Corresponding Author

[**Paper**](https://arxiv.org/abs/2310.17316) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Github**](https://github.com/EnVision-Research/Defect_Spectrum) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Project Page**](https://envision-research.github.io/Defect_Spectrum/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR</div><img src='images/transpixar_after.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TransPixeler: Advancing Text-to-Video Generation with Transparency](https://arxiv.org/abs/2501.03006)

Luozhou Wang, Yijun Li$^{\star}$, **Zhifei Chen**, Jui-Hsien Wang, Zhifei Zhang, He Zhang, Zhe Lin, Yingcong Chen$^{\dagger}$
* $^{\star}$Project Lead  $^{\dagger}$Corresponding Author

[**Paper**](https://arxiv.org/abs/2501.03006) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Github**](https://github.com/wileewang/TransPixar) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Project Page**](https://wileewang.github.io/TransPixar/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/motion_dreamer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Motion Dreamer: Realizing Physically Coherent Video Generation through Scene-Aware Motion Reasoning](https://arxiv.org/pdf/2412.00547)

Tianshuo Xu$^{\star}$, **Zhifei Chen**$^{\star}$, Leyi Wu, Hao Lu, Yuying Chen, Lihui Jiang, Bingbing Liu, Yingcong Chen$^{\dagger}$

* $^{\star}$Equal contribution  $^{\dagger}$Corresponding Author

[**Paper**](https://arxiv.org/pdf/2412.00547) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Github**](https://github.com/EnVision-Research/MotionDreamer) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Project Page**](https://envision-research.github.io/MotionDreamer/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>



# 🎖 Honors and Awards

- **Dean's List Award for Fall 2017 - 2018**  
  Purdue University | 2017

- **Dean's List Award for Spring 2017 - 2018**  
  Purdue University | 2017

- **Dean's List Award for Fall 2016 - 2017**  
  Purdue University | 2016



# 📖 Educations
- *2016.08 - 2020.05, Bachelor of Eng. in Computer Engineering, [Purdue University](https://www.purdue.edu/). 
- *2020.08 - 2022.05, Master of Sci. in Computer Science, [Johns Hopkins University](https://www.jhu.edu/). 
- *2023.08 - (now), Ph.D. in Artificial Intelligence, [HKUST(GZ)](https://www.hkust-gz.edu.cn/).

# 💬 Professional Activities
- International Conference on Computer Vision and Pattern Recognition (CVPR)
- International Conference on Computer Vision (ICCV)
- International Conference on Learning Representations (ICLR)
- European Conference on Computer Vision (ECCV)


# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->