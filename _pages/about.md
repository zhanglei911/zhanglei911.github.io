---
permalink: /
title: "Lei Zhang"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I do research between earthquake engineering and seismology. I simulate seismic waves in multi-scale models based on numerical methods such as the spectral element method (SEM) and the finite element method (FEM). My research interests can be summed up as follows: 

Rupture process of global large earthquakes
======
This is a callabration work with Prof. Chen Ji, Prof. Jinlai Hao and Wenze Deng. I calculate the global 3D Green's function databases based on adjoint simulations using [SPECFEM3D_Globe](https://geodynamics.org/cig/software/specfem3d_globe/). This databased is applied to study the rupture process of large earthquakes in the global scale such as the 2017 Mw8.2 Mexico earthquake, the 2018 Mw 7.9 Alaska earthquake, the 2008 Mw 7.9 Wenchuan earthquake.

Ground motion simulation for engineering purposes
======
I simulate the 3D seismic wave propagation using [SPECFEM3D_Catesian](https://github.com/geodynamics/specfem3d). Near site effects are studied quantificationally such as
* Hanging wall effect
* Topographic effect
* Directivity effect

Rupture-to-structure simulation
======
To numerically simulating the 3D seismic wave propagation from rupture to structures, a two-step method coupling the spectral element method (SEM) and the finite-element method (FEM) is proposed based on the domain reduction method to simultaneously simulate the seismic wave propagation in large-scale regions and analyze the dynamic behavior of structures in local sites. 
* In the first step, the seismic wave propagation of the entire area, involving the source, propagation media, and local region of interest, is simulated using the SEM. 
* In the second step, the dynamic analysis of structure-foundation system with local geological and topographical conditions is implemented using the FEM in a fine mesh based on the results in the first step. 
* The proposed SEM-FEM procedure can well consider the effects of local geological and topographical conditions on synthesized ground motions and can be applied to the rupture-to-structure simulations in earthquake engineering.

Dynamic analysis of structures
======
The large commercial FE software [Abaqus](https://www.3ds.com/products-services/simulia/products/abaqus/) is adopted to analyze the dynamic response for structures, especially for concrete dams.

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

Earthquake-induced disasters
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
