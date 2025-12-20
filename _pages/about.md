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

# 🎓 About Me

I am Yuyang Ding (丁誉洋), a third-year Ph.D. student at the Institute of Artificial Intelligence, Soochow University, advised by [Assoc. Prof. Juntao Li](https://lijuntaopku.github.io) and [Prof. Min Zhang](https://zhangmin-nlp-ai.github.io).

My research interest lies in **RL for LLM Reasoning**, with particular interests in **Agentic RL** and **Robust Reward Modeling**.

I am currently a research intern at ByteDance Seed. My current research focuses on the joint optimization of algorithms and infrastructure to enable scalable and effective reinforcement learning.
- On the algorithmic side, I work on scaling LLM Agents to effectively operate in more complex environments and real-world interactions.
- On the systems side, I focus on scaling reinforcement learning frameworks to efficiently run on large-scale computational resources.

## Research Experience

### Research Intern at ByteDance Seed (25.06 - Present)

- Maintainer and Core Contributor of LLM RL Library [veRL](https://github.com/volcengine/verl), advised by [Chi Zhang](https://sites.google.com/view/chizhang-usc/), [Xibin Wu](https://github.com/wuxibin89), and [Haibin Lin](https://sites.google.com/view/haibinlin/)
- Reinforcement Learning with Generative Rewards (25.06 - 25.10):
  - Algorithm Paper: [FAPO: Flawed-Aware Policy Optimization for Efficient and Reliable Reasoning](https://fapo-rl.github.io/)
  - Infrastructure Design: Asynchronous [Reward Loop](https://verl.readthedocs.io/en/latest/advance/reward_loop.html) design for efficient and Flexible Reward Computation
- Agentic Reinforcement Learning (25.10 - Present):
  - On-going Research, Stay Tuned

### PhD student at OpenNLG group (23.09 - Present)

- Advised by [Juntao Li](https://lijuntaopku.github.io) and [Min Zhang](https://zhangmin-nlp-ai.github.io)
- LLM Reasoning (24.05 - Present):
  - SFT with Synthetic Data: [ScaleQuest: Unleashing LLM Reasoning Capability via Scalable Question Synthesis from Scratch]()
  - Robust Process Reward Modeling: [SCAN: Self-Denoising Monte Carlo Annotation for Robust Process Reward Learning]()
- Robust Learning in Traditional NLP Tasks (23.06 - 24.05):
  - Robust NER: [GNER](https://arxiv.org/abs/2402.16602), [DS-NER](https://www.computer.org/csdl/journal/tk/5555/01/10988654/26tr7cYv7KU); Robust Classification: [SelfMix](https://arxiv.org/abs/2210.04525); Robust QA: [COLDQA](https://arxiv.org/abs/2302.04618).


<!-- **Seeking research internship opportunities in LLM Reasoning and Reinforcement Learning.** -->

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications

**\* denotes equal contribution.**

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/pic-fapo.png' width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FAPO: Flawed-Aware Policy Optimization for Efficient and Reliable Reasoning](https://fapo-rl.github.io)

**Yuyang Ding**, Chi Zhang, Juntao Li, Haibin Lin, Xin Liu, Min Zhang

**TL;DR:** We propose Flawed-Aware Policy Optimization (FAPO), which penalizes flawed patterns to achieve more efficient and reliable reinforcement learning.

[![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2510.22543)
[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/yyDing1/FAPO)
[![](https://img.shields.io/badge/🤗 HuggingFace-Models-green)](https://huggingface.co/collections/dyyyyyyyy/fapo)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/pic-scan.png' width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SCAN: Self-Denoising Monte Carlo Annotation for Robust Process Reward Learning](https://scan-prm.github.io)

**Yuyang Ding**, Xinyu Shi, Juntao Li, Xiaobo Liang, Zhaopeng Tu, Min Zhang

**TL;DR:** We propose Self-Denoising Monte Carlo Annotation (SCAN), an efficient Process Reward Model (PRM) data synthesis and noise-tolerant learning framework.

[![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2509.16548)
[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/yyDing1/SCAN-PRM)
[![](https://img.shields.io/badge/🤗 HuggingFace-Models-green)](https://huggingface.co/collections/dyyyyyyyy/scan-67f0fec64750003ba43d51d3)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/pic-scalequest.png' width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ScaleQuest: Unleashing LLM Reasoning Capability via Scalable Question Synthesis from Scratch](https://scalequest.github.io)

**Yuyang Ding**, Xinyu Shi, Xiaobo Liang, Juntao Li, Zhaopeng Tu, Qiaoming Zhu, Min Zhang

**TL;DR:** We introduce ScaleQuest, a scalable, novel and cost-effective data synthesis method to unleash the reasoning capability of LLMs.

[![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2410.18693)
[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/yyDing1/ScaleQuest)
[![](https://img.shields.io/badge/🤗 HuggingFace-Models-green)](https://huggingface.co/collections/dyyyyyyyy/scalequest-670a7dc2623c91990f28913b)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TKDE</div><img src='images/pic-dsner.png' width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DS-NER: Unveiling and Addressing Latent Noise in Distant Annotations](https://www.computer.org/csdl/journal/tk/5555/01/10988654/26tr7cYv7KU)

**Yuyang Ding**, Dan Qiao, Juntao Li, Jiajie Xu, Pingfu Chao, Xiaofang Zhou, Min Zhang

**TL;DR:** We investigated the noise distribution in distantly supervised annotations and proposed targeted denoising and robust training strategies.

[![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.12454)
[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/yyDing1/DS-NER)
<!-- [![](https://img.shields.io/badge/🤗 HuggingFace-Models-green)]() -->

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/pic-gner.png' width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GNER: Rethinking Negative Instances for Generative Named Entity Recognition](https://arxiv.org/abs/2402.16602)

**Yuyang Ding**, Juntao Li, Pinzheng Wang, Zecheng Tang, Bowen Yan, Min Zhang

**TL;DR:** We introduce GNER, a Generative Named Entity Recognition framework, which demonstrates enhanced zero-shot capabilities across unseen entity domains.

[![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2402.16602)
[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/yyDing1/GNER)
[![](https://img.shields.io/badge/🤗 HuggingFace-Models-green)](https://huggingface.co/collections/dyyyyyyyy/gner-65dda2cb96c6e35c814dea56)

</div>
</div>


<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2022</div><img src='images/pic-selfmix.png' width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SelfMix: Robust Learning Against Textual Label Noise with Self-Mixup Training](https://arxiv.org/abs/2210.04525)

Dan Qiao\*, Chenchen Dai\*, <strong>Yuyang Ding*</strong>, Juntao Li, Qiang Chen, Wenliang Chen, Min Zhang

[![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2402.16602)
[![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/noise-learning/SelfMix)

</div>
</div> -->

- `COLING 2022` [SelfMix: Robust Learning Against Textual Label Noise with Self-Mixup Training](https://arxiv.org/abs/2210.04525),
  
  Dan Qiao\*, Chenchen Dai\*, <strong>Yuyang Ding*</strong>, Juntao Li, Qiang Chen, Wenliang Chen, Min Zhang
  [![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2402.16602)
  [![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/noise-learning/SelfMix)


- `SCIS (CCF-A)` [OpenBA: An Open-sourced 15B Bilingual Asymmetric seq2seq Model Pre-trained from Scratch](https://arxiv.org/pdf/2309.10706),
  
  Juntao Li\*, Zecheng Tang\*, <strong>Yuyang Ding*</strong>, Pinzheng Wang\*, Pei Guo, Wangjie You, Dan Qiao, Wenliang Chen, Guohong Fu, Qiaoming Zhu, Guodong Zhou, Min Zhang
  [![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2402.16602)
  [![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/OpenNLG/openBA)
  [![](https://img.shields.io/badge/🤗 HuggingFace-Models-green)](https://huggingface.co/OpenNLG/OpenBA-V1-Flan)

- `EMNLP 2023` [CMD: a framework for Context-aware Model self-Detoxification](https://arxiv.org/pdf/2308.08295),

  Zecheng Tang, Keyan Zhou, Juntao Li, **Yuyang Ding**, Pinzheng Wang, Yan Bowen, Renjie Hua, Min Zhang
  [![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2308.08295)
  [![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/ZetangForward/CMD-Context-aware-Model-self-Detoxification)
  [![](https://img.shields.io/badge/🤗 HuggingFace-Models-green)](https://huggingface.co/ZetangForward/SegmentCNN)

- `EMNLP 2022` [COLDQA: Robust question answering against distribution shifts with test-time adaptation: An empirical study](https://arxiv.org/pdf/2302.04618)

  Hai Ye, **Yuyang Ding**, Juntao Li, Hwee Tou Ng
  [![](https://img.shields.io/badge/arXiv-Paper-orange?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2302.04618)
  [![](https://img.shields.io/badge/GitHub-Code-blue?logo=github&logoColor=white)](https://github.com/oceanypt/coldqa-tta)
  [![](https://img.shields.io/badge/🤗 HuggingFace-Models-green)](https://huggingface.co/collections/dyyyyyyyy/coldqa-6811d5c684adfa26b82f1f3f)



# 🎖 Honors and Awards
- National Scholarship
- CCF Elite Collegiate Award
- ICPC National Invitational Programming Contest, **Gold Medal**
- ICPC Asia-East Continent Final Contest (EC-Final), **Silver Medal**

# 📖 Educations
- *2023.09 - current*, PhD Student, Institute of Artificial Intelligence, Soochow University
- *2019.09 - 2023.06*, B.Eng., School of Computer Science and Technology, Soochow University

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2025.06 - current*, Research Intern, ByteDance Seed, Shanghai, China,