## Project

The project is an open-ended investigation into an NLP problem.

Project guidelines:

- The data used should be as raw as possible. E.g., you may not simply download a pre-processed dataset from the UCI repository.
- The groups may be up to size 2.
- Sample projects can be found [here](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1194/project.html) or by reading recent papers published in ACL, the top computational linguistics conference: <https://www.aclweb.org/anthology/volumes/2020.acl-main/>
- You may use existing libraries (e.g., nltk, TensorFlow, theano), but your project should be your own.
- Any data needed for your project should be downloaded by the `nlp dl-data` command.
- After the Proposal survey is submitted (see below), a new private repository will be created for your group.
- See the [sample project repo](https://github.com/tulane-cmps6730/sample-project) for how your project will be structured.

### Project Ideas

Submit three project ideas under the "Project Ideas" discussion board on Canvas. Also provide feedback to two other teams.

Complete one survey per team.

### Proposal
Complete the project proposal by submitting under the "Project Proposal" discussion board on Canvas. Also provide feedback to one other team.

You will specify the following:

1. Problem Overview: Describe the problem you are solving; what makes it interesting?
2. Data: Which data will you use? How will you collect it? What problems do you anticipate?
3. Method: What method or algorithm will you use? Will you use an existing library to do so? Do you plan to modify the code at all?
4. Related Work: List at least 5 references (with links) to research papers that are related to your project (use Google Scholar to search).
5. Evaluation: How will you evaluate your results? What baseline method will you compare against? What are the key plots or tables you will produce? What performance metrics will you use? What descriptive evaluation will you do (e.g., look at specific predictions made by your system; visualizations)?

Once you've submitted the form, I will create github repositories for each team, with the appropriate access.

### Milestone

Your project milestone report will be 2 - 3 pages using the provided template in the `report` folder of your project repository. This is essentially a first draft of your final project, with many of the core results missing. The following is a suggested structure for your report:

1. Title, Author(s)
2. Problem Overview: Describe the problem you are solving. State it as precisely as you can.
3. Data: Which data are you using; how did you collect it?
4. Method: What method or algorithm are you using. Are you using an existing library to do so? Did you introduce any new variations to these methods? How will you evaluate the results? Which baselines will you compare against?
5. Intermediate/Preliminary Experiments & Results: State and evaluate your results up to the milestone
6. Related work: Summarize at least five related research papers related to your project. How is your project similar/different?
7. Division of Labor: State which group member is responsible for which aspects of the project.
8. Timeline: What are the remaining steps you plan to complete, and when do you plan to complete them?
9. References: list of references cited in your report.


Compile and push to `report/report.pdf` in your project repo.

You will also provide feedback to one other group under the "Project Milestone" discussion in Canvas.

### Report

A 6-8 page summary of your project. Examples are [here](http://nlp.stanford.edu/courses/cs224n/).

1. Title, Author(s)
2. Abstract: It should not be more than 300 words. What did you do and what was the main conclusion?
3. Introduction: Describe the problem precisely and why it is important.
4. Background/Related Work: Summarize at least five related research papers related to your project. How is your project similar/different?
5. Approach: What method or algorithm are you using. Are you using an existing library to do so? Did you introduce any new variations to these methods? This section details the framework of your project. Be specific, which means you might want to include equations, figures, plots, etc
6. Experiment: What kind of experiments did you do; what kind of dataset(s) you're using; what baseline method are you comparing against; and how you will evaluate your results. Report the results of your experiments in detail, including both quantitative evaluations (show numbers, figures, tables, etc) as well as qualitative evaluations (show images, example results, example errors, etc). Be sure to conduct some "stress testing" of your system using your demo interface. What type of errors does it make and why? Are there any systemic biases you notice in the system (e.g., that would affect one source of data more than others)?
7. Conclusion: What have you learned? Suggest future ideas.
8. References: list of references cited in your report.
9. Screenshots: Include screenshots of your web interface showing a demonstration of your project.

Compile and push to `report/report.pdf` in your project repo.

You should edit the `README.md` file in the root folder of your project repository to include a summary of the report (goals, methods, conclusion, screenshot). This should be a compelling advertisement for your project.

### Presentation

A **maximum** ten minute presentation summarizing your project, following a similar template as the report. Use the `docs/` folder of your project to make your slides using Markdown. The slides should be visible at https://tulane-cmps6730.github.io/project-alpha, where `project-alpha` is your project name. The presentations will be done during Exam week.


### Grading

The project is worth 200 points total, consisting of:
- Project Ideas (10 pts)
- Proposal (20 pts)
- Milestone (30 pts)
- Report:
  - Clarity, related work, discussion (20 pts)
  - Technical correctness and depth (20 pts)
  - Evaluation and results (20 pts)
- Project presentation (20 pts)
- Repository README.md file (10 pts)
- Code quality and thoroughness (30 pts)
- Demo (20 pts)
