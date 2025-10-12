---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
layout: archive
classes: wide
---

<!-- Custom Styles -->
<style>

	/* Sticky navigation bar */
	.masthead {
		position: fixed;
		top: 0;
		width: 100%;
		background: white;
		height: 65px;
	}

	body {
		padding-top: 65px;
	}

	.sidebar {
		top: 65px;
	}

	h1::before {
		display: block;
		content: " ";
		margin-top: -65px;
		height: 65px;
		visibility: hidden;
		pointer-events: none;
	}

	/* Sticky navigation bar end */

	/* Change sidebar settings */
	/* .sidebar {
		opacity: 0.9;
	} */

	/* .author__avatar img {
		max-width: 140px;
	} */

	/* .sidebar {
		font-size: 22px;
	} */

	/* .author__bio,
	.author__urls {
		font-size: 18px;
	} */

	.section-sep {
		margin-bottom: 5px;
		border-width: 0px 0px 2px 0px;
		border-style: solid;
		border-color: #6cb3e0;
	}

	.section-vspace-top {
		margin-top: 30px;
	}

	.vspace-top {
		margin-top: 20px;
	}

	.paper-title {
		font-weight: bold;
	}

	.paper-desc {
		margin-top: 5px;
		text-align: justify;
	}

	.paper-links {
		margin-top: 5px;
	}

	.paper-bib {
		font-size: 14px;
	}

	.paper-authors {
		font-size: 14px;
		font-style: italic;
	}

	.edu-title {
		font-weight: bold;
		margin-top: 2px;
	}

	.edu-desc {
     text-align: justify;
    text-justify: inter-word
  }

	.content {
		text-align: justify;
	}

	.row {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		/*margin-right: -15px;
	margin-left: -15px;*/
	}

	.col {
		-ms-flex-preferred-size: 0;
		flex-basis: 0;
		-webkit-box-flex: 1;
		-ms-flex-positive: 1;
		flex-grow: 1;
		max-width: 100%;
	}

	.col-sm-3,
	.col-sm-4 {
		position: relative;
		width: 100%;
		min-height: 1px;
		padding-right: 15px;
		padding-left: 15px;
	}

	.col-sm-3 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 40%;
		flex: 0 0 40%;
		max-width: 40%;
	}

	.col-sm-4 {
		-webkit-box-flex: 0;
		-ms-flex: 0 0 25%;
		flex: 0 0 25%;
		max-width: 25%;
	}

	.img-fluid {
		max-width: 100%;
		height: auto;
	}
</style>

<!-- ABOUT ===================================================== -->
<div class='section-sep' id="about">
	<h1>About Me</h1>
</div>

<div class='content vspace-top'>
I'm Ph.D. student at the University at Buffalo working with <a href="https://www.buffalo.edu/cear/about-us/leadership-and-administration.host.html/content/shared/engineering/computer-science-engineering/profiles/faculty/ladder/dantu-karthik.html">Dr. Karthik Dantu </a> at <a href="http://drones.cse.buffalo.edu">Distributed RObotics and Networked Embedded Sensing (DRONESLab)</a>. Currently, I am also teaching the CSE568 course at UB. <br>
<br>
My research interests lie at the intersection of motion planning, control and robot learning. I am working on unifying these by leveraging the knowledge from classical techniques as priors for learning based approaches. 
<br>
You can find my resume <a href="/files/yashom_dighe_resume.pdf">here </a>
</div>

<!-- PUBLICATIONS ===================================================== -->
<div class='section-sep section-vspace-top'>
		<h1>Selected Publications</h1>
</div>
<div class='row vspace-top'>
        <div class="col-sm-3">
          <iframe width="320" height="240"
            src="https://www.youtube.com/embed/nX56DGGrWxk?si=O7p7c_XYFVder_eq"
            title="YouTube video player" 
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
			referrerpolicy="strict-origin-when-cross-origin" 
            allowfullscreen>
          </iframe>
        </div>
		<div class="col">
			<div class='paper-title'>
				VISION: Visual Inspection System with Intelligent Observation and Navigation
			</div>
			<div class='paper-authors'>
				<u>Yashom Dighe*</u>, Yash Turkar*, Karthik Dantu
			</div>
			<!-- <div class='paper-bib'>
				Submitted to RAL 
			</div> -->
			<div class='paper-desc'>
              Culverts along canals like the Erie Canal require regular inspection but are difficult for humans to access due to their geometry, lighting, and environmental conditions. We present VISION, a language-guided autonomous inspection system that integrates a vision–language model with constrained viewpoint planning. Brief prompts generate open-vocabulary defect proposals, depth fusion recovers scale, and a planner commands the robot to capture targeted re-images. Deployed on a quadruped in real culverts, VISION achieved up to 80% agreement with expert assessments.
			</div>
			<div class='paper-links'>
				<a href="https://ieeexplore.ieee.org/document/10341603" target="_blank">[paper]</a>
				<a href="https://arxiv.org/abs/2509.21370" target="_blank">[Project Page]</a>
			</div>
		</div>
	</div>
<!-- KFC ----- -->
<div class='row vspace-top'>
		<div class="col-sm-3">
		 <video width="320" height="240" controls>
            <source src="/assets/video/kfc.mp4" type="video/mp4">
            <source src="movie.ogg" type="video/ogg">
    		Your browser does not support the video tag.
		</video> 
		</div>
		<div class="col">
			<div class='paper-title'>
				KFC: Kinematics Only Differential Flatness based Control for F1Tenth Autonomous Racing
			</div>
			<div class='paper-authors'>
				<u>Yashom Dighe</u>, Youngjin Kim, Smit Rajguru, Yash Turkar, Tarunraj Singh, Karthik Dantu
			</div>
			<div class='paper-bib'>
				2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 
			</div>
			<div class='paper-desc'>
				In this work, we show the effectiveness of Differential Flatness based control for high-speed trajectory tracking for car-like robots. We demonstrate a 15% increase in trajectory tracking performance compared to MPC while reducing the required compute by more than 50%, both in simulation and on a real 1:10 scale race-car.
			</div>
			<div class='paper-links'>
				<a href="https://ieeexplore.ieee.org/document/10341603" target="_blank">[Paper]</a>
			</div>
		</div>
	</div>
  
<!-- KFC ----- -->

<!-- Current Research  ===================================================== -->
<div class='section-sep section-vspace-top'>
		<h1>Current Research</h1>
</div>

<!-- <div class='row vspace-top'>
  <div class="col">
    <div class='edu-title'>
      Differential Flatness based Trajectory Generation for Autonomous Racing [Project Page (Coming Soon)]
    </div>
    <div class="edu-desc">
    </div>
  </div>
</div> -->

<div class='row vspace-top'>
  <div class="col">
    <div class='edu-title'>
      Extending visual planning to 3D spaces using Gaussian Splatting and Imitation Learning[Project Page (Coming Soon)]
    </div>
    <div class="edu-desc">
      <!-- We want to do xyz -->
    </div>
  </div>
</div>

<div class='row vspace-top'>
  <div class="col">
    <div class='edu-title'>
      <a href="https://droneslab.github.io/EARTH" target="_blank">EARTH: Excavation Autonomy with Resilient Traversability and Handling</a> 
    </div>
    <div class="edu-desc">
      

Excavators, earth-movers, and large construction vehicles have been instrumental in propelling human civilization forward at an unprecedented pace. Recent breakthroughs in computing power, algorithms, and learning architectures have ushered in a new era of autonomy in robotics, now enabling these machines to operate independently. To this end, we introduce EARTH (Excavation Autonomy with Resilient Traversability and Handling), a groundbreaking framework for autonomous excavators and earth-movers. EARTH integrates several novel perception, planning, and hydraulic control components that work synergistically to empower embodied autonomy in these massive machines. This three-year project, funded by MOOG and undertaken in collaboration with the Center for Embodied Autonomy and Robotics (CEAR), represents a significant leap forward in the field of construction robotics.

    </div>
  </div>
</div>

<!-- <div class='row vspace-top'>
  <div class="col-sm-4">
    May 2018 - Dec. 2021
  </div>
  <div class="col">
    <div class='edu-title'>
      NASA Goddard Space Flight Center - Wallops Flight Facility
    </div>
    <div class="edu-desc">
      Pathways Student, Wallops Systems Software Engineering Branch (Code 589)<br>
      Cube/Small-satellite Flight Software
    </div>
  </div>
</div>

<div class='row vspace-top'>
  <div class="col-sm-4">
    Sep. 2019 - Jan. 2020
  </div>
  <div class="col">
    <div class='edu-title'>
      NASA Jet Propulsion Laboratory
    </div>
    <div class="edu-desc">
      Intern, Robot Operations Group (347K)<br>
      Simulation, Mars 2020 Rover Operations
    </div>
  </div>
</div>

<div class='row vspace-top'>
  <div class="col-sm-4">
    Jan. 2019 - Jan. 2020
  </div>
  <div class="col">
    <div class='edu-title'>
      NOVI Aerospace
    </div>
    <div class="edu-desc">
      Machine Learning Consultant<br>
      Dataset Curator
    </div>
  </div>
</div>

<div class='row vspace-top'>
  <div class="col-sm-4">
    Mar. 2016 - May. 2020
  </div>
  <div class="col">
    <div class='edu-title'>
      UB Nanosatellite Laboratory
    </div>
    <div class="edu-desc">
      Flight Software Lead (~15-45 Students)<br>
	  Three CubeSat Missions
    </div>
  </div>
</div> -->

<!-- EDUCATION ===================================================== -->
<div class='section-sep section-vspace-top'>
	<h1>Education</h1>
</div>

<div class='row vspace-top'>
  <div class="col-sm-4">
        Jan. 2024 - Present
	</div>
  <div class="col">
    <div class='edu-title'>
      University at Buffalo
    </div>
			<div class="edu-desc">
				PhD, Computer Science and Engineering<br>
        Distributed RObotics and Networked Embedded Sensing (DRONES) Lab<br>
        Advised by Dr. Karthik Dantu<br>
			</div>
		</div>
</div>

<div class='row vspace-top'>
  <div class="col-sm-4">
        Aug. 2022 - Dec. 2023
	</div>
  <div class="col">
    <div class='edu-title'>
      University at Buffalo
    </div>
			<div class="edu-desc">
				M.S. in Robotics
			</div>
		</div>
</div>

<div class='row vspace-top'>
  <div class="col-sm-4">
        Aug. 2016 - May 2020
	</div>
  <div class="col">
    <div class='edu-title'>
      Mumbai University
    </div>
			<div class="edu-desc">
				B.E. in Computer Science
			</div>
		</div>
</div>



