# AI-Powered-Resume-Screening-Tool


## About

Resume GPT is an efficient recruitment assistant powered by OpenAI's GPT-3.5. The tool allows recruiters to upload multiple resumes along with a job description. You can further specify mandatory keywords that should be present in a candidate's resume. As a result, the tool will provide an evaluation of each resume against the provided job description and give insights into the suitability of the candidate for the role.

## Features

- Bulk upload of resumes in PDF format.
- Specification of a job description to compare the resumes against.
- Option to add mandatory keywords for the desired candidate profile.
- Analysis of resumes using OpenAI GPT-3.5 to generate suitability remarks.
- Downloadable results in a CSV format with columns for resume name, comments, and suitability.

## Requirements
- Flask
- OpenAI Python Client
- pdfplumber(it is a library which is used to extract the data from the pdf's)
- CSV module

## Setup

1. Clone the repository.

2. Change directory to the cloned repository.

3. Install the required packages.

4. Update the OpenAI API key in the openai.api_key = "OPEN AI KEY" line with your own key.
   
5. Run the application.
```
python screening_tool.py
```

## Usage

1. Access the tool by visiting in your browser.
2. Upload the desired resumes.
3. Provide a detailed job description.
4. Specify any mandatory keywords that you want to be present in the candidate's resume.
5. Click on "Submit" to get the analysis.
6. You can then download the results in a CSV format.

## Limitations

1. As the tool uses the OpenAI API, you will need a valid API key which might have associated costs.
2. The current version supports resumes in PDF format only.

