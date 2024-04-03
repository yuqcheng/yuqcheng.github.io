---
layout: page
title: experience
permalink: /experience/
description: 
nav: False
nav_order: 2
_styles: ../assets/css/timeline.css
# display_categories: [work, fun]
horizontal: false

---
<link rel="stylesheet" href="../assets/css/timeline.css">

<body>
<hr>
<!-- The Timeline -->

<ul class="timeline">
<!-- Item 1 -->
<li>
	<div class="direction-l" data-toggle="modal" data-target="#mit">
		<div class="flag-wrapper">
			<span class="flag">MIT Bonnie Berger Lab</span>
			<span class="time-wrapper"><span class="time">Summer 2023</span></span>
		</div>
		<div class="desc">
			<b>Research Assistant</b> <br>
			Diffusion models/scHi-C
		</div>
	</div>
</li>

<!-- Item 1 -->
<li>
	<div class="direction-l" data-toggle="modal" data-target="#cmu">
		<div class="flag-wrapper">
			<span class="flag">CMU Jian Ma Lab</span>
			<span class="time-wrapper"><span class="time">Summer 2022</span></span>
		</div>
		<div class="desc">
			<b>Research Assistant</b> <br>
			 Hyper-SAGNN/Gaussian Process Uncertainty
		</div>
	</div>
</li>

<!-- Item 2 -->
<li>
	<div class="direction-r" data-toggle="modal" data-target="#zhang">
		<div class="flag-wrapper">
			<span class="flag">GT Xiuwei Zhang Lab</span>
			<span class="time-wrapper"><span class="time">2021 - present</span></span>
		</div>
		<div class="desc">
			<b>Research Assistant</b> <br>
			GNNs and Spatial Transcriptomics<br>
		</div>
	</div>
</li>

<!-- Item 2 -->
<li>
	<div class="direction-l" data-toggle="modal" data-target="#bbi">
		<div class="flag-wrapper">
			<span class="flag">Boundless Bio</span>
			<span class="time-wrapper"><span class="time">Summer 2021</span></span>
		</div>
		<div class="desc">
			<b>Bioinformatics Intern</b> <br>
			ecDNA Analytics and WSI pipeline <br>
		</div>
	</div>
</li>

<!-- Item 3 -->
<li>
	<div class="direction-r" data-toggle="modal" data-target="#gt">
		<div class="flag-wrapper">
			<span class="flag">Georgia Tech</span>
			<span class="time-wrapper"><span class="time">2020 - 2023</span></span>
		</div>
		<div class="desc">
			<b>Bachelors in Computer Science </b> <br>
			Specializing in ML/Theory <br>
			GPA: 4.0/4.0
		</div>
	</div>
</li>

</ul>




<div id="timeline">
	<!-- Timeline Item, copy from here to create various boxes -->
	<div class="modal fade" id="mit" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
		<div class="modal-dialog" role="document">
			<div class="modal-content">
				<div class="modal-header">
					<h5 class="modal-title" id="exampleModalLabel"><img src="../assets/img/mit.png" width="50vw" height="40vh">  &nbsp; &nbsp; MIT Bonnie Berger Lab &nbsp; &nbsp; <img src="../assets/img/broad.png" width="120vw" height="40vh"></h5>
					<button type="button" class="close" data-dismiss="modal" aria-label="Close">
					<span aria-hidden="true">&times;</span>
					</button>
				</div>
				<div class="modal-body">
					<p><i class='fas fa-id-badge'></i> &nbsp;Research Assistant </p>
					<p>
						<ul>
						<li>Diffusion models for genome structure (via scHi-C imputation) and protein structure conformational change.</li>
						<li>Accepted into the Broad Summer Research Program (BSRP) starting June</li>
						</ul>
					</p>
					<p><i class='fas fa-calendar'/> &nbsp;May 2023 - Present</p>
					<p><i class='fas fa-map-marker-alt'></i> <em>&nbsp;Cambridge, MA </em> </p>
				</div>
			</div>
		</div>
	</div>
	<div class="modal fade" id="cmu" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
		<div class="timeline-item">
			<div class="modal-dialog" role="document">
				<div class="modal-content">
					<div class="modal-header">
						<h5 class="modal-title" id="exampleModalLabel"><img src="../assets/img/cmu.png" width="50vw" height="50vh">  &nbsp; &nbsp;  CMU Jian Ma Lab </h5>
						<button type="button" class="close" data-dismiss="modal" aria-label="Close">
						<span aria-hidden="true">&times;</span>
						</button>
					</div>
					<div class="modal-body">
						<p><i class='fas fa-id-badge'></i> &nbsp;Research Assistant </p>
						<p>
							<ul>
							<li>Using Hypergraph GNNs to predict trigenic interactions in the yeast genome, specifically those with ESM protein structural significance</li>
							<li>Applying Gaussian Processes to pair our model's predictions with an uncertainty score</li>
							</ul>
						</p>
						<p><i class='fas fa-calendar'/> &nbsp;Dec 2021 - Present</p>
						<p><i class='fas fa-map-marker-alt'></i> <em>&nbsp;Carnegie Mellon University, PA </em> </p>
						<!-- <a href="#" class="btn">button</a> -->
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="modal fade" id="zhang" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
		<div class="timeline-item">
			<div class="modal-dialog" role="document">
				<div class="modal-content">
					<div class="modal-header">
						<h5 class="modal-title" id="exampleModalLabel"><img src="../assets/img/gt.png" width="50vw" height="50vh">  &nbsp; &nbsp; GT Xiuwei Zhang Lab </h5>
						<button type="button" class="close" data-dismiss="modal" aria-label="Close">
						<span aria-hidden="true">&times;</span>
						</button>
					</div>
					<div class="modal-body">
						<p><i class='fas fa-id-badge'></i> &nbsp;Research Assistant </p>
						<p>
							<ul>
							<li>Developed <a href="https://academic.oup.com/bioinformatics/article/39/Supplement_1/i484/7210503">CLARIFY</a>, a method for refinining extracellular and intracellular interactions with graph neural networks and Spatial Transcriptomics data</li>
							<li>Accepted for oral presentation at ISMB</li>
							<li>Recieved best poster award at AWSOM, PURA Salary Award, and PURA Travel Award</li>
							<li>Benchmarking current Spatial Transcriptomics + CCI methods</li>
							</ul>
						</p>
						<p><i class='fas fa-calendar'/> &nbsp;Nov 2021 - Present</p>
						<p><i class='fas fa-map-marker-alt'></i> <em>&nbsp;Atlanta, GA </em> </p>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="modal fade" id="bbi" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
		<div class="timeline-item">
			<div class="modal-dialog" role="document">
				<div class="modal-content">
					<div class="modal-header">
						<h5 class="modal-title" id="exampleModalLabel"><img src="../assets/img/ppi_trans.png" width="50vw" height="50vh">&nbsp;Boundless Bio</h5>
						<button type="button" class="close" data-dismiss="modal" aria-label="Close">
						<span aria-hidden="true">&times;</span>
						</button>
					</div>
					<div class="modal-body">
						<p><i class='fas fa-id-badge'></i> &nbsp;Bioinformatics Research Intern </p>
						<p>
							<ul>
							<li>Provisional patent for creating metaDetect: a computer vision algorithm for identifying metaphase spreads in stained WSI of cancer cells using image filtering techniques</li>
							<li>Created automated pipeline for whole slide imaging → metaDetect (CV) → ecDNA quantification (CNN)</li>
							</ul>
						</p>
						<p><i class='fas fa-calendar'/> &nbsp;Aug 2020 - Dec 2021</p>
						<p><i class='fas fa-map-marker-alt'></i><em>&nbsp;San Diego, CA </em> </p>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div class="modal fade" id="gt" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
		<div class="timeline-item">
			<div class="modal-dialog" role="document">
				<div class="modal-content">
					<div class="modal-header">
						<h5 class="modal-title" id="exampleModalLabel"><img src="../assets/img/gt.jpeg" width="48vw" height="45vh">&nbsp; BS/MS in Computer Science</h5>
						<button type="button" class="close" data-dismiss="modal" aria-label="Close">
						<span aria-hidden="true">&times;</span>
						</button>
					</div>
					<div class="modal-body">
						<b><i class='fas fa-graduation-cap'></i> &nbsp;BS in Computer Science</b>
						<p>
							<ul>
							<li>GPA - 4.0/4.0</li>
							<li>Specializing in Machine Learning/Theory</li>
							<li>B.S. complete May 2023</li>
							</ul>
						</p>
						<p><i class='fas fa-calendar'/> &nbsp;Aug 2020 - Dec 2023
						<p><i class='fas fa-map-marker-alt'></i> <em>&nbsp;Atlanta, GA</em> </p>
						</p>	
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
<br>
<br>
<hr>
<br>
<br>
</body> 
