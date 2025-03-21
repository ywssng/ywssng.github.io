---
title: 'Stochastic Resetting Mitigates Latent Gradient Bias of SGD from Label Noise'

# design:
#   spacing:
#     padding: [0, '1rem', 0, '1rem'] # top, right, bottom, left

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  # - "Youngkyoung Bae$^*$"
  # - "Yeongwoo Song$^*$"
  - "Youngkyoung Bae"
  - "admin"
  - "Hawoong Jeong"

# Author notes (optional)
author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - ""

date: '2024-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard. 'paper-conference', 'article-journal', 'article' (preprint)
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: 'In *Machine Learning: Science and Technology*'
publication_short: "In *Mach. Learn.: Sci. Technol.* 6 (2025) 015062"

abstract: Giving up and starting over may seem wasteful in many situations such as searching for a target or training deep neural networks (DNNs). Our study, though, demonstrates that resetting from a checkpoint can significantly improve generalization performance when training DNNs with noisy labels. In the presence of noisy labels, DNNs initially learn the general patterns of the data but then gradually memorize the corrupted data, leading to overfitting. By deconstructing the dynamics of stochastic gradient descent (SGD), we identify the behavior of a latent gradient bias induced by noisy labels, which harms generalization. To mitigate this negative effect, we apply the stochastic resetting method to SGD, inspired by recent developments in the field of statistical physics achieving efficient target searches. We first theoretically identify the conditions where resetting becomes beneficial, and then we empirically validate our theory, confirming the significant improvements achieved by resetting. We further demonstrate that our method is both easy to implement and compatible with other methods for handling noisy labels. Additionally, this work offers insights into the learning dynamics of DNNs from an interpretability perspective, expanding the potential to analyze training methods through the lens of statistical physics.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - physics for ai
  - statistical physics
  - stochastic resetting
  - learning noisy labels
  - robust regularization


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: 'https://iopscience.iop.org/article/10.1088/2632-2153/adbc46'
url_pdf: 'https://arxiv.org/pdf/2406.00396v3'
url_code: 'https://github.com/qodudrud/stochastic-resetting'
# url_dataset: 
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->