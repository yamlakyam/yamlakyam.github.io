---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student in Biomedical Informatics at Indiana University, currently working at the AIMeD Lab under [Prof. Rakesh Shiradkar](https://luddy.indianapolis.iu.edu/people/rakesh-shiradkar.html). I completed my M.S. degree in Electrical and Computer Engineering at Carnegie Mellon University in 2024. Previously, I obtained my B.Sc. in Electrical and Computer Engineering from Addis Ababa University. I have also worked at the [AI Healthcare Lab](https://www.africa.engineering.cmu.edu/research/ai-healthcare.html) at CMU-Africa under [Prof. Carine Mukamakuza](https://www.africa.engineering.cmu.edu/about/contact/directory/bios/mukamakuza-carine.html). My research focuses on histopathology image analysis, multimodal integration, and AI for cancer diagnosis and prognosis.


News and Updates
======
- Nov 2025: Travel Grant, awarded by WiML to attend NeurIPS 
- Oct 2025: 2 Papers accepted at SPIE Medical Imaging
- Oct 2025: 2 Abstracts accpeted at USCAP
- Sep 2025: A Poster accepted at NeurIPS WiML workshop 
- Jan 2025: Started my PhD at Indiana University
- Dec 2024: Travel Grant, awarded by BlackinAI to attend NeurIPS
- Nov 2024: Poster accepeted at the BlackinAI workshop colocated with NeurIPS
- Nov 2024: Our workshop paper got accepted at NeurIPS Climatechange.ai workshop
- May 2024: Completed my Masters at Carnegie Mellon University and awarded the [Rising Researcher Jeremiah Mpagazehe Award](https://www.africa.engineering.cmu.edu/news/2024/05/30-graduation.html)
- Mar 2024: Featured in [Mastercard Foundation's Impact stories](https://mastercardfdn.org/en/what-we-do/impact-stories/remember-to-stay-connected-to-your-roots/)
- Feb 2024: HighRisers Fellow, selected as one of 20 Women in Data Science fellows and paired with seasoned professional mentors.
- Nov 2023: Travel Grant, awarded by [Cylab Africa/Upanzi Network](https://www.africa.engineering.cmu.edu/research/upanzi/index.html) to attend and present a poster at the 2nd [West African Conference on Digital Public Goods and Cybersecurity](https://www.africa.engineering.cmu.edu/events/conferences/digital-infrastructure-cybersecurity/index.html).
- May 2023: ICLR Registration Grant, awarded by Women in Machine Learning to attend the International Conference on Learning Representations (ICLR) held in Kigali, Rwanda.
- July 2023: Travel Grant, awarded by Carnegie Mellon University Africa, and presented the essay “Human Singularity: An Enigma” (inspired by the course Artificial Cognitive Systems) at the 19th [South American Business Forum](https://www.sabf.org.ar/conference/about/) in Buenos Aires, Argentina.
- Feb 2022: Google African Developers Award, by Google Africa in partnership with Andela and Pluralsight to receive a scholarship to take the Associate Android Developer Track.
- Dec 2021: People's Choice Award at #HACK2021, awarded by Indigitous for building a mobile application that helps youth connect with their spiritual life.
- Dec 2020: Very Great Distinction, awarded by the School of Electrical and Computer Engineering at Addis Ababa University.

  


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
