# Workshop-Web-Retrieval-and-Scraping

![Logo](https://github.com/yashraj9011/Workshop-Web-Retrieval-and-Web-Scraping/blob/main/WRS_Workshop.png)

## Introduction Morning Session
- Speaker addressed to students by introducing their profile and the domain they are working in .
- He Started from Computer Networking basics , how data flows in the systems .
- Idea about what is web scraping , its need and how it is done in the industry .

## Implementation in Jupyter Notebook 

<script>
    // Replace 'your_md_file.md' with the path to your Markdown file
   // const mdFilePath = 'Workshop on Web Scraping.md';
const mdFilePath = 
    // Fetch the Markdown file
    fetch(mdFilePath)
        .then(response => response.text())
        .then(mdText => {
            // Convert Markdown to HTML using showdown.js
            const converter = new showdown.Converter();
            const htmlContent = converter.makeHtml(mdText);

            // Display the HTML content in the designated element
            document.getElementById('markdown-content').innerHTML = htmlContent;
        })
        .catch(error => {
            console.error('Error fetching the Markdown file:', error);
        });
</script>



