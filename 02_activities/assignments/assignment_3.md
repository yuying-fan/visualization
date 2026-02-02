# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    Python and R

    > Who is your intended audience? 
    Public health officials and those interested in health data trends

    > What information or message are you trying to convey with your visualization? 
    The first visual is a bar chart looking at which health care settings are most effected by outbreaks. Showing how long-term care homes carry disproportionate outbreak burdens.
    The second visual looks at how these outbreaks are recurring and cyclic, with large increases during major health crises and never seem to fully return to baseline.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    - Clarity -> minimal chart elements, no unnessecary grid lines, titles and clear axis labels
    - Readability -> rotate x-axis labels
    - Although visual 2 is wide, the image is in high-definition and can be zoomed in to look at section by section
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    - Both visuals are reproducible. The codes for generating them as well as the reports (downloaded from https://open.toronto.ca/dataset/outbreaks-in-toronto-healthcare-institutions/) can be found in the assignment_3 folder.

    > How did you ensure that your data visualization is accessible?  
    - Using clear color contrasts (white background; blue bars or lines);Avoiding red/green color combinations
    - Adding descriptive titles and axis labels
    - Removing unnecessary visual noise
    - The image of the visuals are posted onto this public Github; which is accessible on various browser types
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    - Patients in long-term care homes, and their families
    - Healthcare workers that would be exposed to these repeating increasing outbreaks
    - Public health officials that are involved in outbreak control

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    The original dataset contains columns of id, Institution Name, Institution Address, Outbreak Setting, Type of Outbreak, Causative Agent-1, Causative Agent-2, Date Outbreak Began, Date Declared Over, Active. Since the goal of these two visuals was to examine larger system-level patterns in healthcare outbreaks, I included the columns of outbreak setting and date outbreak began. First, outbreak setting was used to compare which types of healthcare institutions experience the highest number of outbreaks. Next, Data Outbreak began was chosen to construct a monthly time-series showing how number of outbreaks change over time.

    
    > What ‘underwater labour’ contributed to your final data visualization product?
    - Installing and configuring R
    - Combining multiple year files together
    - Fixing axis scaling and layout issues in the visual


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
