---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Robust Point Cloud Based Reconstruction of Large-Scale Outdoor Scenes"
authors: [Ziquan Lan, Zi Jian Yew, Gim Hee Lee]
#date: 2019-07-09T10:42:08+08:00
date: 2019-06-16
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: 2019-07-09T10:42:08+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Computer Vision and Pattern Recognition (CVPR)"
publication_short: ""

abstract: "Outlier feature matches and loop-closures that survived front-end data association can lead to catastrophic failures in the back-end optimization of large-scale point cloud based 3D reconstruction. To alleviate this problem, we propose a probabilistic approach for robust back-end optimization in the presence of outliers. More specifically, we model the problem as a Bayesian network and solve it using the Expectation-Maximization algorithm. Our approach leverages on a long-tail Cauchy distribution to suppress outlier feature matches in the odometry constraints, and a Cauchy-Uniform mixture model with a set of binary latent variables to simultaneously suppress outlier loop-closure constraints and outlier feature matches in the inlier loop-closure constraints. Furthermore, we show that by using a Gaussian-Uniform mixture model, our approach degenerates to the formulation of a state-of-the-art approach for robust indoor reconstruction. Experimental results demonstrate that our approach has comparable performance with the state-of-the-art on a benchmark indoor dataset, and outperforms it on a large-scale outdoor dataset. Our source code can be found on the project website."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code: https://github.com/ziquan111/RobustPCLReconstruction
url_dataset:
url_poster: "poster_cvpr19_robustPCL.pdf"
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=ZZQT_REkItU

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
