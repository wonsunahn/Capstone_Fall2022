---
layout: page
permalink: /projects/
---

# Capstone Project List - WORK IN PROGRESS

Projects will soon be posted in this page!


## Industry Capstone Projects

### [Database Performance Optimizations Using SQLite]({{site.baseurl}}/projects/pdfs/NetApp-SOS-Pitt-Capstone-Abstract-Fall-2022.pdf)

**_Project Background_**

[ONTAP®](https://www.netapp.com/data-management/ontap-data-management-software/) is NetApp’s proprietary operating system powering a wide variety of hardware- and software-based data storage and retrieval systems, including storage disk arrays and cloud- hosted storage offerings. It helps users to create a storage infrastructure that reduces cost, accelerates critical workloads, and secures data. With countless operations going on in such systems every second, a high-functioning scalable database engine can have a massive impact on the system enabling higher scalability and faster data access speeds.
SQLite is a widely used open-source software library that provides a relational database management system with full SQL support. It is feature-rich and highly configurable at compile and runtime. Using a series of optimization approaches interacting with SQLite, it is possible to realize significant savings using system resources and/or improve transaction performance. Undertaking database performance improvements can help us identify bottlenecks in the current design and enable the system to handle ever-increasing workloads.
For this Capstone project, NetApp is looking to explore the efficiencies and the optimizations of using SQLite to further improve the performance of ONTAP® and provide a better user experience for our customers.

**_Project Summary_**
In this project, students will work on developing and testing various SQLite performance improvements. They will work on analyzing the results of the changes to see which improvements lead to more performant database operations. The creative student team can propose additional features and improvements to implement and test in collaboration with the NetApp engineering lead.

**_Project Goals_**
- Implement and run performance tests to analyze the impact of different changes in the use of SQLite as well as changes to SQLite library source code.
- Present the results to NetApp engineers along with recommendations on which improvements to keep.
- Stretch goal – Test additional improvements based on team’s investigation and findings.

**_Project Details_**
Over the course of this Capstone project, students will utilize several programming languages and concepts, including:
- Coding in C/C++ to interact with SQLite library.
- Making changes to open-source software projects.
- Learning and enacting modern testing methodologies and practices.
- Working with a large relational database to run the performance testing on.
- Using Agile development.


### CGI - [Client Onboarding]({{site.baseurl}}/projects/pdfs/UniversityofPittsburghCGICapstoneFall2022ProjectOnboarding.pptx)

**Check the PDF (link in the title)**

* Team Size: 5/6 students
* POC: Anthony DeLuca (anthony.deluca@cgi.com), Patrick Collins (patrick.collins@cgi.com)

### CGI - [Prototype for Code vs Model based deployment with end to end model monitoring/tracking]({{site.baseurl}}/projects/pdfs/UniversityofPittsburghCGICapstoneFall2022ML.pdf)

**Check the PDF (link in the title)**

* Team Size: 3/4 students
* POC: Surya Patchipala (surya.patchipala@cgi.com), Anthony DeLuca (anthony.deluca@cgi.com)


## CS Faculty Projects

### Data Science for Countering Hate
Hate speech and hate crimes have surged across the world -- both online and offline. In Europe, instances of antisemitic, anti-Muslim, and other racist hate crimes have grown ​​at an alarming rate in many countries. In the US, hate crimes rose last year to the highest level in more than a decade -- more than half of hate crime incidents were motivated by bias against the victim's race, ethnicity, or ancestry, with a rise in assaults targeting Black and Asian Americans. During the coronavirus pandemic, social media platforms have become the main venues for the dissemination of hate-motivated behaviors. This project aims to create data science tools that analyze hate-motivated messages and their relationship with offline extremist events. We will develop tools that automatically collect relevant social media posts and extract features from texts that are predictive of offline hate. These tools will contribute to the fight against hate by supporting researchers, journalists, and inspectors to conduct qualitative or quantitative content analyses.

**Project Details**: Over the course of this Capstone project, students will utilize several programming languages and data analytic packages. Students are expected to know or easily learn the following:
**_Essential skillset_**
    - Python/R; familiarity with data/text mining packages to create feature extraction component
    - HTTP and data scraping tools to interact with RESTful APIs
    - GitHub
- Basic knowledge of Social Networks and Graph Theory.
- Basic knowledge of NLP tasks, such as text embeddings, POS, NER, etc.
- Front-end programming tools (i.e. React / JavaScript) to create interfaces and/or new visualization components. 
* Team Size: 2 students
* POC: Yu-Ru Lin (yurulin@pitt.edu) and Ahmad Diab (AHD23@pitt.edu)



### Monitoring Africa's Food Insecurity from Text Data
The COVID-19 pandemic, climate crisis, regional conflicts, and the war in Ukraine have altogether created severe food shortages across multiple countries in Africa. ​​More than 23 million people are experiencing extreme hunger in Ethiopia, Somalia, and Kenya, which is more than double the previous year. The ongoing war disruptions the global food supply chain, causing a surge in food prices worldwide, and now, African countries are facing the worst food crisis since 1945. This project aims to create a monitoring system for the ongoing food crisis that will identify events, policies, and other socioeconomic factors directly or indirectly linked to food insecurity in the region. We will develop tools that automatically collect relevant news reporting and extract features from texts that are predictive of future food crises. The project will contribute to the fight against world hunger by building a data-driven knowledge base.

**_Project Details_**: Over the course of this Capstone project, students will utilize several programming languages and data analytic packages. Students are expected to know or easily learn the following:
**_Essential skillset_**
- Python/R; familiarity with data/text mining packages to create feature extraction component
- HTTP and data scraping tools to interact with RESTful APIs
- GitHub
- Deep learning library such as pytorch to run experiments

* Team Size: 2 students
* POC: Yu-Ru Lin (yurulin@pitt.edu) and Yongsu Ahn (yongsu.ahn@pitt.edu)



### Behavior, Fairness, and Safety in Traffic Control

In recent years, several studies proposed different Reinforcement Learning (RL) methods and formulations for the Traffic Signal Control problem, presenting promising results and flexible traffic light solutions. Some of the studies investigate technical AI aspects (e.g., different neural network architectures, transfer learning, RL models, etc.), the coordination problem (e.g., distributed systems), while others are interested in the implementation side of things (e.g., Systems/IoT), just to name a few of the interests. 

For this project, the focus is to verify how RL adaptive systems handle not only efficiency (e.g., minimize time loss) but also other important aspects of traffic control, namely, behavior changes in traffic flow due to expected and unexpected events, fairness between the different actors of the system, and safety (e.g., accidents prevention).

Depending on the team interests, some topics/ideas include:
    - pedestrian, cyclist, public transportation, and emergency vehicle oriented
        - Detecting pedestrian activity (e.g., how many people and how long are they waiting to cross the street?)
        - Handle fairness between vehicles and pedestrians; Give exclusivity to one in the absence of the other, within reason.
        - Prioritize (virtual) bus corridors and promote quality of service (e.g., prioritize buses that are running late by extending the green light)
        - Communicate emergency vehicle's route so the correct flows are prioritized in time; provide early notice to vehicles so they can open the way earlier (i.e., vehicles on the next block be already prepared when the emergency vehicle arrives); prioritize emergency vehicles even when they are not engaged in an active emergency
    - weather, disruptions events, and safety aware
        - Adapt traffic control to inclement weather (e.g., rain, snow, and fog, all of which make driving more dangerous and need to be studied)
        - Detect anomalies in traffic behavior (e.g., accidents, constructions sites, emergencies, break-downs, debris, etc.) and automatically adapt signals to it; 
        - Understand accidents patterns and prevent them through traffic control (and vice versa!);

We are looking for self-motivated, independent individuals who are interested in real-world problems and applied AI. In this project, you will work with traffic simulators (e.g., Sumo, CityFlow) and RL. Python language is required for this project, and RL knowledge, although not required, may provide you with the opportunity to explore and experiment more within the time frame.

Base References:
https://smartpittsburgh.org/
https://www.cmu.edu/traffic21/

* Team Size: 3/4 students
* POC: Marcelo D'Almeida (marcelo@pitt.edu)

### RAWRS 
For DECADES CS 447 was taught using MIPS assembly language. However, MIPS processors are not that common anymore (RIP PS and PS2) (they still live in network equipment though :).
On the other hand, the RISC-V architecture (open-source) is gaining some momentum, and you can even buy some boards to have fun with it.

We are still using MARS (which we all hate ;), but we want to push the development of an alternative that uses RISC-V. wilkie developed a web-based alternative, but it's still not ready for primetime: https://gitlab.com/wilkie/rawrs
This tool is called RAWRS (RISC-V Assembler and Workable, Rewritable System) - it's an acronym it can mean whatever we want! - and it's a web-based tools (bye bye Java).

The objective for this project is to develop this tool further to a point where it can be used for CS 447.
- Review and test existing implementation.
- Adapt the website (Javascript development) to new functionality (implement plugins).
- Fix any outstanding/detected bugs in the software.

The tool is written in (modern) Javascript where we predict most of the development will be focused. But you will also have the opportunity to stretch your assembly muscles. As the RISC-V simulator is backed by a RISC-V kernel :D

* Team Size: 3 students
* POC: Luis Oliveira (loliveira@pitt.edu)


### Allegheny County Policing Project (ACPP) v.2.0

Since June 2020, Center for Analytical Approaches to Social Innovation student and community-led teams have been building web tools to help grassroots racial justice organizations. Our work reflects the contribution of more than 170 volunteers. In Fall 2021, CAASI launched 412Connect - a Black-owned Business scavenger hunt platform (news here and here), and Allegheny County Policing Project (ACPP) - a tool for Allegheny County residents to navigate our 100+ police departments and their complicated accountability rules (Year of Data and Society video here, 1Hood Power Hour video here).

As we work to be able to replicate the ACPP website for other counties around the country (as a part of our 2022-2023 Pitt Seed project Building Data Science for Social Justice (DS4SJ)), generalizations and improvements to the site are required. For Fall 2022, we will need students interested in full stack web development to both: update the backend to better support other counties and update the frontend to improve the user experience accounting for the results of several user studies we have performed. 

* Team size: 3/4 students
* You will be working with:
    - Capstone advisor: Prof Nick Farnan (SCI)
    - CAASI Director: Prof Sera Linardi (GSPIA)
    - CAASI Tech leads: Patrick Gavazzi (Tuft's), Collin Griffin
    
### A Web Framework for Social Justice
Since June 2020, Center for Analytical Approaches to Social Innovation student and community-led teams have been building web tools to help grassroots racial justice organizations. As we work to spin up more web projects to further these goals, we want to avoid "reinventing the wheel" with every new initiative. As a part of our 2022-2023 Pitt Seed project Building Data Science for Social Justice (DS4SJ), we aim to build a skeleton project of best practices for new web projects. Towards this aim, we're looking for a team of students interested in full stack web development to research best practices, bundle the best components for the job together into a single project, streamline deployment of this project via Docker, develop sample tests for all project components, and write documentation to guide users of this framework. Our goal is to use this as a starting point, so that future projects can hit the ground running.
* Team size: 3/4 students
* You will be working with:
    - Capstone advisor: Prof Nick Farnan (SCI)
    - CAASI Director: Prof Sera Linardi (GSPIA)
    - CAASI Tech leads: Patrick Gavazzi (Tuft's), Collin Griffin


### Interactive website to help students plan their academic career in the Data Science major

This capstone project aims at providing an interactive website to help students plan their academic career in the Data Science major. The website should allow a user (a student) to select courses of interest from a list. Upon selection, a network diagram will be visualized which includes not only the course(s) the user selected, but also all pre-requisite courses required to take before the selected course(s). This tool will allow the student to plan their trajectory path through the major. The visualization tool should be fully interactive, allowing the user to move the elements of the network diagram around the screen and change the colors as they see fit. The tool should allow the user to download a file containing the trajectory path so the student may store in their records. Time permitting, it would be great if several recommended trajectory paths could be provided as options to the user.

There are no specific technology requirements for completion, except that it should be easy for someone with permissions to modify and/or add courses. This will let the tool grow and change as the major changes. Students do not need to identify courses within the major. All courses currently associated with the Data Science major have been catalogued. An example static network diagram is shown below. The project goal is to create a fully dynamic and interactive version of this diagram that can be tailored to a specific student.

* Team size: 3/4 students
* POC: Joseph Yurko (JYURKO@pitt.edu)

### Gradescope and Project development for CS0401

This team will be working on porting existing auto-testing tools used in CS0401 to Gradescope.
Once that task is done, you will be developing new projects to be used in CS0401 and graded in that system.

This project is open ended, so you will have the opportunity to discuss which projects and what they will look like as part of the project.

* Team size: 3 students
* POC: Tim Hoffman (hoffmant@pitt.edu)

## Other Capstones

### UMS - Visual Novel Game
This is a game development project that will pick up an already existant codebase and further develop it.

Desired Features:
- Biggest Feature: Ability to parse in written scripts that is interpreted into content (see below)
- Start Screen with Menu Options New Game, Load Data, Options, Extra, and Exit
- Phone Feature: Check document
- Unique Backlog Feature
- Staple VN Features

**Check Canvas for details**

* Team Size: 3/4 students
* POC: Bortnick, Justin (jabortnick@pitt.edu)



 
<!--SO FAR: 34+ -->





<!--SO FAR: 



Please file your top THREE choices as an issue with a title beginning with PROJECT (will go over in class) by Wednesday (26 January) morning at 11:59 AM (i.e., right before noon). Please list them in the order that you prefer them.  You will be informed as to your project BY the next Capstone class on Friday (28 January). YOU MUST FILE AN ISSUE IN ORDER TO BE PLACED ON A PROJECT AND THUS GET CREDIT FOR THE COURSE!  YOU WILL NOT BE PLACED ON A PROJECT IF YOU DO NOT FILE AN ISSUE!

REMEMBER TO ADD "PROJECT" TO THE BEGINNING OF YOUR ISSUE TITLE!

Along with your selections, please include any qualifications or specific reasons for interest that you have for those specific projects. Remember that you are "interviewing" for the project against others, especially if you have selected popular projects. Students who respond early also show enthusiasm for the projects, which goes a long way to showing that they actually want to do them.

I will attempt to place you in one of your top three choices. Usually, every student gets into one of their top three (and a majority into their #1 choice), although I cannot make any guarantees.

Note: Some of you may be working on private projects. Please file an issue on this repository (as above) but note that you have already been assigned to a project. List the project and the name of the POC (e.g. faculty member or supervisor). If we have not discussed you being placed on a private project, do not put yourself on one.

## Industry Capstone Projects

[Develop a kernel extension for an Open Source File System]({{site.baseurl}}/projects/pdfs/NetApp-SOS-Pitt-Capstone-Abstract-Spring-2022.pdf)

**_Project Background_**
Embedded and distributed systems focused projects are not commonly provided at a bachelor’s level Capstone project.  Our goal is to provide an opportunity for aspiring embedded systems engineers to gain experience in this area utilizing an open source embedded file system as a base for developing a specific kernel extension.
Developers at NetApp have been optimizing and enhancing our embedded proprietary file system (WAFL – write anywhere file layout) for over 20 years.  Because of the proprietary nature of the file system we will be using an open source equivalent for this project.   Working in the C language, students will gain real-life experience developing for embedded, distributed systems.

**_Project Summary_**

In this project, students will work with the FUSE open source file system installed on Ubuntu Linux platform. The project team will work through the detailed steps below to implement a kernel extension that reports the file system space usage.
Project Details 
 Over the course of this Capstone project, students will accomplish the following high-level goals: 
•	Download and install FUSE on Linux.
•	Work through a NetApp provided initial custom example to understand the basic architecture.
•	Create a read/write file system as an underlying test bed and explore the properties of this system.
•	Write the kernel extension (using the C programming language) to implement a user space reporting function.
•	Execute automated tests during the writing of the kernel extension.  Enhance the automated tests as necessary.
•	Enhance the file system to store user space consumed data in an in-memory database.
•	Update the in-memory database based on incoming fileops.
•	Implement a space enforcement feature which prevents write fileops that exceed a defined usage limit.


 
**_About NetApp_**   
NetApp is the Data Authority in the Hybrid Cloud.
Throughout the world, leading organizations count on NetApp for software, systems, and services to manage and store their data. We help enterprises and service providers envision, deploy, and evolve their IT environments. Customers also benefit from our open collaboration with other technology leaders to create the specific solutions they need.  
Our team is passionate about customer success. Our company culture and work environment support that dedication. Together with our global network of partners, we are united in one goal: to help our customers achieve the outcomes that matter most to them. To learn more, visit www.netapp.com. 
The project is driven by the Scale Out Storage team which provides the file system infrastructure within the kernel to achieve high performing, scalable containers that are a key component of the NetApp Data Fabric architecture.
NetApp At-A-Glance 
•	$6.0B+ in revenue 
•	Over 10,000 employees in more than 150 offices worldwide 
•	Great Place to Work Institute's "World’s Best Multinational Workplaces" list 
•	Great Place to Work Institute’s “Best Companies to Work for in APAC” list 
•	Great Place to Work Institute’s “Best Companies to Work for in Europe” list 
•	FORTUNE Magazine's "100 Best Companies" list 
•	A FORTUNE 500® Company 
•	Member of S&P 500 and NASDAQ 
•	Stock symbol: NTAP 
•	Close partnerships with global industry leaders.



### CGI - [Client Onboarding]({{site.baseurl}}/projects/pdfs/CGI.pdf)

**Check PDF** 

**Project Overview**
To enhance and improve a client-onboarding portal that serves as an Onboarding and Knowledge Management solution, designed to make the process of onboarding new CGI members to project teams more efficient and effective. Students will work with a team of CGI experts to not only help solve this problem/challenge but also learn critical skills needed as they enter the workforce.

**Project Details**

The proposed Onboarding and Knowledge Management portal will achieve a couple of objectives:
* UI Redesign
* Implement Responsive formatting. 
* Modify Notifications Quick View
* Generating reports from retrieved database information.
* Add Notifications Confirmation for Project Manager.

The outcome of this Capstone Project would be a software solution that meets these objectives, along with its associated artifacts like architecture documentation, user personas, user journeys/workflows, UI/UX prototypes, software development environment setup, code documentation, testing artifacts, etc.

Students should expect to learn about modern software-development techniques in an enterprise setting such as:
* Design-thinking methodologies
* Ideation and UI/UX rapid prototyping
* Agile software development
* Product and Project management
* State-of-art technologies

Students are expected to know or easily learn the following technologies:
* Angular (TypeScript, HTML/CSS)
* Spring Boot (Java)
* Jsoup
* Sonarcube
* Docker
* Git
* MySQL
* IntelliJ/VS Code
* Trello


* Team Size: 5/6 students
* POC: Anthony DeLuca (anthony.deluca@cgi.com)


**Note: NDA and/or IP agreement will need to be signed for this project.**

### CGI - [Banking Ticketing support ]({{site.baseurl}}/projects/pdfs/CGI2.pdf)

**Check PDF** 

**Project Overview**
Our goal is to categorize Banking Ticketing support text information automatically which is extracted from historical support tickets and matching a given category with the correct recipient using Distilled BERT Text Classification.
For our implementation, we choose the BERT model, due to its popularity, performance and availability of open-source implementations.

**Project Details**

The proposed Onboarding and Knowledge Management portal will achieve a couple of objectives:
* Understand Text Classification Algorithms
* Implement few Text Classification Algorithms in local CPU
* Analyze the accuracy and performance metrics
* Train the high accuracy Text Classification model in Cloud
* Crete pipelines for the end-end deployment using TensorFlow and GPU’s.
* Create end points on the Text Classification model
* Create explainability algorithm on top the model
* Automate/End point creation for the explainability algorithm


The outcome of this Capstone Project would be a software solution that meets these objectives, along with its associated artifacts like architecture documentation, user personas, user journeys/workflows, UI/UX prototypes, software development environment setup, code documentation, testing artifacts, etc.

Students should expect to learn about modern software-development techniques in an enterprise setting such as:
* Design-thinking methodologies
* Ideation and UI/UX rapid prototyping
* Agile software development
* Product and Project management
* State-of-art technologies

Students are expected to know or easily learn the following technologies:
* Python
* Cloud Technology (Azure)
* Basic Machine Learning
* Explainability Algorithms
* Git
* SQL Database (Any cloud persistence DB) 
* IntelliJ
* Trello


* Team Size: 8/10 students
* POC: Anthony DeLuca (anthony.deluca@cgi.com)


**Note: NDA and/or IP agreement will need to be signed for this project.**



## CS Faculty Projects

### Video Portals to Foster Lightweight Team Building Across Disciplines

Faculty and students across Pitt’s School of Medicine and School of Computing and Information, as well as CMU’s Heinz School of Business are embarking on new collaborations to bridge medicine and mixed-reality technologies.  Stakeholders have labs spread across both campuses, each are equipped with conferencing cameras and large displays.  We are seeking to leverage this infrastructure to create multimedia portals between lab spaces.  We envisioned utility of these persistent portals will be able to foster awareness and “water cooler” conversations across teams.  The envisioned system would support multiple modalities of interaction, including synchronous video (e.g. Zoom style streams), short asynchronous video (e.g. TikTok style videos), and feeds from Discord channels.  We are seeking a capstone team to lead the implementation of this vision.  An ideal team would be interested in multimedia and social technologies. Student will have access to mentors across stakeholder organizations. They will also have access to lab spaces and technologies to prototype and test their technologies.

* Team size: 3-4
* POC: Prof Jacob Biehl, Ph.D. (CS/SCI), Dr Edward Andrews, M.D. (Neurosurgery, PittMed/UPMC)


### Smart displays for indoor navigation

This project will be integrated with a Masters Project. A Masters student is working on an application that facilitates navigation of people across buildings. Think navigating hospital corridors to go get an x-ray without staff guidance.

As part of his project, we need to develop some wireless devices to help different people with navigation. The exact mean of transmitting information is still to be decided. But will likely require programming an embedded device (likely programmed in C), and assembling some LEDs or other display devices (don't worry, we will help with those things as needed).

Good skills to have:
* C programming
* Building simple circuits (not really required, we'll help)

* Team size: 3-4 students
* POC: Prof Jacob Biehl, Ph.D. (CS/SCI), Luis Oliveira

### Using explainable AI to understand and develop voice privacy

In this project, we will explore the use of explainable AI to understand and develop obfuscation functions to keep your voice private while asking voice assistants (like Alexa) for help with tasks. We are currently exploring ML techniques and Neural Net models to classify voice emotions (e.g., happy, angry, scared, sad). Our goal is to use AI techniques to develop functions to obfuscate a subset of emotions considered private (e.g., angry and scared) while allowing other emotions (e.g., sad and happy) to be still classified. Successful transformations (call it "defense") will allow the non-private emotions to be classified while inhibiting or hindering the classification of other emotions. The software environment needs to be deployed in a GPU-enable server. This project will carry out the following tasks (meet weekly and check code, data, results in GitHub). A summary of the tasks:

1. Read our brief summary of the book "Profiling humans from their voice" describing voice privacy issues and watch the video for a fast introduction.
2. Implement three ML models to classify emotions. You can find an example with Decision Trees and Random Forests here.  Read and understand the software environment (what are the inputs, outputs, how inputs are read, what configurations exist, what are the different options for utility, defenses, and attacks).
3. Modify the software to also collect the following metrics: Accuracy, F1, false positives, and false negatives.
4. Search and implement 2 more Datasets, run the software, produce results similar to existing results but with new datasets (for all metrics).
5. Isolate the results per dataset (only evaluate with single datasets and compare the results).
6. Use the Shap library to explain the results from step 2 and rank the features in order of importance.
7. Retrain the models from step 2 while removing the most important features of a particular emotion (based on step 6) for each sample.
8. Process and plot the results.
9. Analyze the outputs and write a final report.
10. If results from step 8 results are unsatisfactory, repeat step 7 with a different approach for removing features.  


* Team size: 2-3 students
* POC: Henrique Potter (potter.cs@pitt.edu)


### Pitt Cyber Range - Active RST Attack Lab

**_About the Pitt Cyber Range_**

The Pitt Cyber Range is a sandboxed environment to simulate real cybersecurity attacks and defenses, which are challenging to perform on a personal computing machine. It allows learners to understand not only how sophisticated attacks work, but also develop the necessary skills to protect humans, information, systems, networks, and critical infrastructure. In addition to learning how to find and exploit flaws, learners develop an understanding about the underlying issues and an ability to articulate reasons and remedies to threats.

**_About the Project_**

The major challenge in performing a RST attack is to (a) successfully forge a RST packet that has the correct sequence number and (b) have the forged RST packet arrive at the destination before the legitimate packet.

The purpose of this project is to develop a hands-on exercise for students to experience performing a successful RST attack. The student team will develop a **_Python_** script (which uses Python’s [sockets](https://realpython.com/python-sockets/) and [Scapy](https://scapy.net/)) that runs on two Kali Virtual Machines (VMs) to send/receive data in a way that makes RST attacks feasible. The script should include enough “wait” times to allow students (simulating an attacker) the opportunity to send their forged RST packet and send it to either VMs such that it can be accepted. In addition, the script should be able to detect correct RST packets received and restart the communication. The student team should be able to also demo the project by successfully forging a RST packet and sending it to either Kali VMs.

To minimize the reporting burden on students using this lab and the grading burden on faculty, students will be asked to include an email address in the payload of the forged RST packet such that the script can send an automated email to the student (and the instructor) indicating the success of the attack. If there’s time remaining in the semester, the script, developed by the student team, should (a) inspect the payload of any successful RST packet to find the email address (of the student performing the lab) and (b) send an email to that email indicating the success of the attack.



* Team size: 3-4 students
* POC: Ahmed Ibrahim  (aibrahim@pitt.edu)


### The skills of college education and successful careers PI: Prof. Morgan R. Frank

Which colleges give their students relevant skills for the future of work? Which majors or fields of study are most effective at workforce development? Data on skills and workplace activities are essential for describing labor trends in the workforce, but data on the skills taught during workforce development--- in higher education in particular---remain absent. Although workers’ skills shape their career opportunities, few studies describe the skills taught to college students. This project will fill this gap using a novel data set of 10 million university course syllabi to empirically study the skills and abilities taught in courses over the last decade. This project will detect the empirical skills taught in university/college classrooms and compare these skills to workers’ resumes based on workers’ educational metadata.

The syllabus data include the university, year, and field of study of each college course which enables us to describe the skill profiles of universities and college majors. We will detect skills (according to a taxonomy used by the US Bureau of Labor Statistics) using one of two approaches: either an NLP approach using word embeddings or by connecting the syllabus data to other datasets relating occupations to skill profiles. Deliverables for this project include:

- Design data cleaning code to process the syllabus data and other data sources
- Create a network connecting college majors and universities to occupations and skills
- Create an interactive web-visualization (e.g., using javascript/D3) that enables users to explore
the network

* Team size: 3-4 students
* POC: Prof. Morgan R. Frank (MRFRANK@pitt.edu)


### GUI for AppArmor

Bill Garrison and Jack Ullery (a newly-graduated Pitt CS alum) have been working on a project for about 8 months in which they are developing a graphical interface for AppArmor. AppArmor is a Linux kernel extension that can enforce per-process access controls. Similar to mobile platforms which allow users to restrict individual apps from accessing files other than their own, AppArmor is used to restrict which resources can be accessed by individual Linux processes. This can be used as a type of sandbox; if a vulnerability is exploited, AppArmor rules can prevent the exploited process from exfiltrating information other than the minimum it needs to run normally.

AppAnvil is our graphical interface for AppArmor, which aims to mitigate barriers to entry for non-experts to use the module. The goal is for it to function somewhat like a modern software firewall, allowing users to configure what is allowed vs. blocked after reviewing historical accesses. The current interface is relatively simple, and the team will expand it to implement additional functionality and improve the organization and usability of the current functionality. The team will first need to become familiar with running a Linux VM and writing code that uses C++, GTK, and the AppArmor API; then learn the overall structure of the existing code before making contributions. Deep systems knowledge is not necessary, as we will be interacting with (but not modifying) the existing AppArmor kernel module. The team will meet weekly with Jack and bill, and work closely with Jack who will guide the team through studying the prerequisite information (e.g., the structure of the existing code, how AppArmor is typically used).

Required skills: 
* Object-oriented programming

Preferred, but not required, skills: 
* Linux command line
* Running consumer VMs
* git version control
* C++ programming
* interface design or HCI
* unit testing

* Team size: 4-5 students
* POC: Bill Garrison (bill@cs.pitt.edu)

### [Language Revitalization Game (link)](https://docs.google.com/document/d/1ZwBaGdPmPtuh9_YobtqD5oEYgWchlaOW4uX5cVLGyIo)
The purpose of this project is to design and implement a game that would help preserve and revitalize the Yup'ik and Gwich'in languages. 

The proposed game-based environment will initially consist of three levels.  In the first level, learners will be presented with culturally-representative and historically accurate environments of the indiginous Yup'ik and Gwich'in speakers.  One example of such an environment could be  a 3D video game rendering of a Yup'ik fishing camp.  The learner with the guidance of an elder Yup’ik  will have an opportunity to explore the in-game world from a first person perspective and interact with various objects that are representative of the Yup'ik culture.  For example, a learner may experience fishing from a virtual canoe, or explore the smoking house, and learn how to build a fish rack.  While exploring these environments and interacting with in-game objects, learners will be presented with objects’ descriptions and relevant stories in both Yup'ik and English.  As the game progresses, English translations of Yup'ik texts will become more and more sparse, and learners will have to demonstrate knowledge of Yup'ik vocabulary in order to progress and to unlock interactions with more objects.

In the second level, learners will be presented with a series of quests based on Yup'ik and Gwich'in subsistence traditions, and based on knowledge and understanding of a specific traditional craft, such as how to make a fish rack.  In order to solve each of the quests, the learner will have to examine multimedia and text related to the problem at hand (e.g. watch a video about traditional fish rack building methods, or read a chronicle of how to fish). Multimedia and text will be presented in a combination of the target language(s) and English.  As the learner progresses through Level 2, English descriptions of the core concepts will be phased out and slowly replaced by respective Yup'ik and Gwich'in text and/or utterances. Moreover learners will be presented to the ecological cultural conception of nature in these indigenous populations. They will be introduced to the link that the indigenous populations perceive between the natural and spiritual world and how language transmits this link. For example, they will learn how in these tribes they do not simply fish or hunt animals but how the animals give themselves to the people in order to fulfil their need for subsistence.

The third level will build on top of the first and second levels and augment the story and the narrative with the introduction of conversational non-player characters (NPCs).  These NPCs will integrate NLP ML models trained on corpora of multimodal Yup'ik and Gwich'in data, including text, images, video, and audio.  Learners will be able to practice contextually relevant and culturally appropriate conversational skills by interacting with the NPCs, asking them questions and processing their responses in order to solve presented quests. One example of such an interaction may include a scenario where the learner plays the role of a character in a Yup'ik or Gwich'in legend and has to converse with other characters represented by conversational NPCs in order to play through the narrative.  Another example for the Gwich’in tradition may include a scenario where the learner has to collaborate with the NPCs in an adventure in which both transform into animals or acquire some animal superpowers such as the wolverine to complete a quest. In both of these scenarios, dialog and interaction with the NPCs are necessary to complete the work and to progress through the level.  

The learner will have access to a schema that explains how the language is used in the specific quest context. Through these schemas that illustrate the full interaction, the learners will be encouraged to pursue the game while learning how to use the language. The language presented in the schemas also gives the learners the opportunity of different choices of expressions to use in the situation so that they can develop agency in using the more adequate language option to express themselves while completing the quest.

* Team size: 4 students
* POC: Dmitriy Babichenko (dmb72@pitt.edu)

## Projects with external people

### Film Network Web App
 
As algorithmic recommender systems take over the consumption of movie-going through streaming platforms, it grows increasingly difficult for everyday viewers to diversify their taste in films that transcends what their specific streaming service offers. The film network web application overcomes this problem by showing a film's cinematic "family tree"—that is, its key movie ancestors, stylistic siblings, and progeny—in two key ways: (1) displaying multiple graph network views of cinematic connections (whether that be from film movements, tracing influence, reviews, or the people involved) and (2) inviting users to create profiles and participate by suggesting new film relationships in their page, or discuss in the forum of a particular page by making arguments for additional, not-yet-written-about relationships. Users will be able to search for any film and discover possible family tree branches for each film, along with quotes from (and links to) existing writing( in the page’s crowdsource bibliography) and users' submitted written arguments, so that users can further consider—and endorse and reply to—proposed connections.
 
The purpose of this application is to encourage users to explore more cinematic work created throughout its existing history by placing the films on a timeline in relationship with each other instead of limiting themselves to only consume the newest films. This tool will help users find new connections in films, allowing them to experience the many innovations and approaches of which cinema operates.
 
Applicable Skills: 
* SQL/Neo4j towards database queries
* CSS and Javascript for front end
* Python, Flask, or Pyramid for the back end


* Team Size: 3 Students
* POC: Jeff Heinzl (Visiting Lecturer, English Department) jmh173@pitt.edu


### Project: [Allegheny County Policing Project (ACPP) v.2.0](https://www.grieftoaction.org/#/)

Since June 2020, [Center for Analytical Approaches to Social Innovation](http://caasi.pitt.edu) student and community-led teams have been building web tools to help grassroots racial justice organizations. Our work reflects the contribution of more than 170 volunteers.  In Fall 2021, CAASI launched [412Connect](https://www.412connect.org/) - a Black-owned Business scavenger hunt platform (news [here](https://www.yearofdataandsociety.pitt.edu/kickoff-data-and-society-conversation-zeroes-connecting-black-owned-businesses-students) and [here](https://www.pitt.edu/pittwire/accolades-honors/412connect-project-transforms-grief-action)), and [Allegheny County Policing Project (ACPP)](https://www.grieftoaction.org) - a tool for Allegheny County residents to navigate our 100+ police departments and their complicated accountability rules (Year of Data and Society video [here](https://drive.google.com/file/d/12-d2hUd4INB1YHoq4_6PrfFGFfDRRYJE/view), 1Hood Power Hour video [here](https://www.youtube.com/watch?t=1102&v=W1MNkl4Isaw)).  

The national police reform nonprofit Campaign Zero and activists from Hennepin County (Minneapolis, MN) have approached CAASI with a request to replicate or expand the ACPP website to other counties. Our goal for Spring 2022 is to take the existing site and turn it into a Python package. We hope to rewrite the site's various functionalities (eg. [interactive police dept map](https://www.grieftoaction.org/#/map), [police contract search function](https://www.grieftoaction.org/#/researchers), misconduct complaint tool) into neatly documented modules for the package. This way other counties would be able to create their own police contract navigator simply by installing the package and populating a pre-designed Google sheet.  

Project goals: 
* Add continuous integration (CI) testing to ensure software quality and integrity
* Automate creation of Docker images for easy deployment for outside community organizations
* Make currently “hard-coded” values modifiable by creating configuration files for use by community organizers
* Redo entire workflow for gathering input municipality and police contract data
* Refactor data storage, including a rewrite of the database schema and rewrite of in-memory representations

* Team size: 3/4 students
* You will be working with:  
    - Capstone advisor: Prof Nick Farnan, SCI
    - CAASI Director: Prof Sera Linardi, GSPIA
    - CAASI Tech lead: Collin Griffin, SCI

### Authoring system for evaluating surgical skill

**Background**

Surgeon trainees spend a great deal of time in the operating room learning how to perform surgeries. However, unlike students in classrooms, they do not take tests. Instead, they are observed and rated during surgeries in the operating room by experienced attending surgeons. These evaluations take time, and so many surgeons don’t do them often enough. Mobile apps are being touted as a potential solution, but they have a significant limitation. They do not give the surgeon the ability to decide what skills they want to rate. This is a problem because residents have to learn entirely different skills for different procedures. For example, a General Surgery resident has to learn at least 130 procedures. Current mobile apps approach this by simply making the rating scales very general and broad, which doesn’t help residents know how they are really doing. It also doesn’t ensure that patients will get a surgeon with the right skills.

The goal of this project is an app optimized for smart phones with two functions: an evaluator side in which a surgeon can rate a resident’s skills and a manager side in which the same surgeon can author the criteria they want to rate their residents on. Ultimately, the app should result in more surgeons rating their residents more often on procedure-specific skills.

A typical scenario would be the surgeon wants to create an evaluation form for a procedure. The surgeon logs into the manager side of the app and free-text enters the name of each skill and resident they want to evaluate. The surgeon has to decide how best to score that skill, so a list of scale types is available to choose from (yes/no; likert scale 0-5; text box; etc). Once done, the form appears on the evaluator side of the app. The evaluator side also displays boxes for the name of the procedure name and an interactive calendar for the date of the surgery. After the resident has performed a surgery, the attending launches the app and fills out an evaluation for them. Later, the resident may log in to see their evaluation data which can be visualized in several ways. They can see a composite score of every time they have performed this procedure. They can drill down to see whether specific skills are getting better over time. The attending surgeon can also see this data. The visualization of data helps the attending and resident talk about how to improve on what skills.

* Team size: 3/4 students
* POC: Eliza Beth Littleton, Research Associate Professor at the Department of Surgery (bethlittleton@pitt.edu)








## Bioinformatics/Computational Biology projects (**CS students can apply to some**)


### Optimizing Molecular Simulations in the WESTPA Software

**_Main project_**
With any given computational resource, there is always a decision whether we should run multiple short independent simulations (can be run in parallel) vs. one long simulation (longer history correlation between trajectories). Students would analyze the weighted ensemble simulations from both protocols, correlating the efficiency (wall-clock time, CPU time, aggregated simulation time) vs. convergence to the known rate of association, understanding the advantages/disadvantages of both.
 
**_Advanced goals_**
Weighted Ensemble simulations typically require a long time to fully converge to the desired ensemble (Steady State or Equilibrium) from initial starting conditions. In order to speed up the process, we can employ reweighting schemes to adjust trajectory weights based on existing data, further nudging the system towards the desired ensemble. WESS and haMSM are two such reweighting protocols available for WESTPA. WESS calculates the steady state bin-to-bin transitions to predict WE bin population, then reweight the trajectories from the last iteration in a per-bin basis. haMSM creates a history augmented markov state model (a MSM with information on which state it was previously from), calculate the steady state population of each MSM-bin and start a new simulation using trajectories reweighed based on the WE weights and MSM bin occupation. Students would try to compute the efficiency of each protocol to see how quickly it converges to the expected rate of association.

* Team size: 2/3 students
* POC: Jeremy Leung (JML230@pitt.edu) and Anthony Bogetti


### Improving 3Dmol.js, an online WebGL molecular viewer

**CS students can apply**

In this project students will work on 3Dmol.js (https://3dmol.org/), a JavaScript library of hardware accelerated molecular graphics. Projects will be tailored to the interests of the student.  Some possible projects include:
 - adding support for more molecular dynamics file formats (straightforward javascript)
 - user interface improvements (javascript + design)
 - implement improved transparency options (javascript + WebGl shaders)
 - implement new molecular visualizations (javascript + chemistry)

All projects will make extensive use of JavaScript.  In some, but not all, cases knowledge of jQuery, WebGL, or chemistry will be needed.

* Team size: 3/4 students
* POC: David Koes (dkoes@pitt.edu)


### Takis Benos group

- **Project 1** - Use ML algorithms (like VAEs) to extract features for clinical images (X-rays or CT scans). Then use the features, together with microbiome, genetic and clinical data, to cause-effect relations and build predictors of clinical outcomes.

- **Project 2** - Use graph algorithms (like our ssNPA) to identify macrophage cell subtypes related to aging in the lung.  We already have a compendium of scRNA-seq data to work on.

- **Project 3** -  Develop a new causal learning algorithm for multinomial data distributions.  Application to gene expression regulatory network reconstruction.

* Team size: 2/3 students per project
* POC: Takis Benos (benos@pitt.edu)
?-->