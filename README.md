## Welcome to Fangni's Homepage

Dr. Fangni Zhang will join the Department of Industrial and Manufacturing Systems Engineering at The University of Hong Kong as an Assistant Professor in February 2020. Prior to this, she held Lecturer positions at University of New South Wales and University of Leeds, and worked at Imperial College London as a Research Associate. Dr. Zhang received her PhD degree in Transportation from Hong Kong University of Science and Technology and her Bachelor’s degree in Industrial Engineering from Beihang University, Beijing, China.

Dr. Fangni Zhang’s research covers a wide range of fundamental or emerging issues in transport, including multimodal transport system modelling and optimization, shared and automated transport management, high-speed rail and air transport interactions, and wider economic impacts of transport. Her research draws tools from different disciplines such as network modeling, economic theory, traffic flow theory, operations research, and data science to transport research and has been published in a number of world-leading journals and conferences in the field (e.g., Transportation Research Part A, B, C, D, E).

### Research interests

- Transport and logistics management
- Multimodal transport systems
- High-speed rail and air transport
- Automated and shared mobility
- Wider economic benefits quantification
- Transport and urban data analytics

### PhD positions

- I am looking for 1-2 self-motivated Ph.D. students to join my research group. Applicants should have a B.S. or M.S. in Industrial Engineering, Transportation Engineering, Economics, Operations Research, Mathematics, and Computer Science or related fields. Strong oral and written communication skills in English are required. Candidates with research experience in network modeling, optimization and game theory are preferred.

- Successful applicants will be considered eligible to receive a Postgraduate Scholarship (the 2019/20 rate: HKD 17,330/month) during the normative study period. Outstanding applicants for the Ph.D. programme are strongly encouraged to apply for the Hong Kong PhD Fellowship scheme, which offers an annual stipend of HKD 25,800 /month plus a conference and research-related travel allowance of HKD 12,900 per year for a period of up to three years. More information regarding HKU Ph.D. scholarships is available at:
https://www.gradsch.hku.hk/gradsch/prospective-students/scholarship-funding-and-fees#2
To learn more about the HKU Ph.D. programme, visit 
https://www.gradsch.hku.hk/gradsch/prospective-students/why-choose-hku  

- The application deadline for 2020 intake is 2 December 2019. Please contact Dr. Fangni Zhang directly at fangni.zhang@hotmail.com

- Postdoc and visiting research positions are also available. If your research background fits my research interests, please send me your CV including your education qualifications and list of publications (if any).

### Selected Publications

• **Zhang, F.**, Graham, D.J., Wong, M. (2018) Quantifying the substitutability and complementarity between high-speed rail and air transport. Transportation Research Part A, 118, 191-215. 

• **Zhang, F.**, Zheng, N., Yang, H., Geroliminis, N. (2018) A systematic analysis of multimodal transport systems with road space distribution and responsive bus service. Transportation Research Part C, 96, 208-230.

• Liu, W., Li, X, **Zhang, F.**, Yang, H. (2017) Interactive travel choices and traffic forecast in a doubly dynamical system with user inertia and information provision. Transportation Research Part C, 85, 711-731.

• **Zhang, F.**., Liu, W., Wang, X., Yang, H. (2017) A new look at the morning commute with household shared-ride: How does school location play a role? Transportation Research Part E, 103, 198-217.

• Liu, W., **Zhang, F.**, Yang, H. (2017) Modeling and managing morning commute with both household and individual travels. Transportation Research Part B, 103, 227-247.

• Wang, W.W., Wang, D.Z., **Zhang, F.**, Sun, H., Zhang, W. and Wu, J. (2017) Overcoming the Downs-Thomson Paradox by transit subsidy policies. Transportation Research Part A, 95, 126-147.

• **Zhang, F.**, Lindsey, R. and Yang, H. (2016) The Downs–Thomson paradox with imperfect mode substitutes and alternative transit administration regimes. Transportation Research Part B, 86, 104-127.

• Liu, W., **Zhang, F.**, Yang, H.  (2016) Managing morning commute with parking space constraints in the case of bi-modal many-to-one network. Transportmetrica A, 12(2), 116-141.

• **Zhang, F.**, Yang, H., Liu, W. (2014) The Downs-Thomson Paradox with responsive transit service. Transportation Research Part A, 70, 244-263.

• Liu, W., Yang, H., Yin, Y., **Zhang, F.** (2014) A novel permit scheme for managing parking competition and bottleneck congestion. Transportation Research Part C, 44, 265-281.

A Github Pages template for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is Â© 2016 Michael Rose and released under the MIT License. See LICENSE.md.

I think I've got things running smoothly and fixed some major bugs, but feel free to file issues or make pull requests if you want to improve the generic template / theme.

### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

# Instructions

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

# Changelog -- bugfixes and enhancements

There is one logistical issue with a ready-to-fork template theme like academic pages that makes it a little tricky to get bug fixes and updates to the core theme. If you fork this repository, customize it, then pull again, you'll probably get merge conflicts. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch. 

To support this, all changes to the underlying code appear as a closed issue with the tag 'code change' -- get the list [here](https://github.com/academicpages/academicpages.github.io/issues?q=is%3Aclosed%20is%3Aissue%20label%3A%22code%20change%22%20). Each issue thread includes a comment linking to the single commit or a diff across multiple commits, so those with forked repositories can easily identify what they need to patch.


