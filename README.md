<!--
*** Thanks for checking out the question-answering. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username (that is "windsuzu"), repo_name (that is "question-answering"), project_title, project_description
-->

<!-- [![Issues][issues-shield]][issues-url] -->
[![Contributors][contributors-shield]][contributors-url]
[![MIT License][license-shield]][license-url]
[![PR Welcome][pr-welcome-shield]](#contributing)
[![Author][author-shield]][author-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/windsuzu/question-answering">
    <img src="images/logo.png" alt="Logo" width="100" height="100">
  </a>

  <h3 align="center">Question Answering</h3>

  <p align="center">
    Question Answering
    <br />
    <a href="https://github.com/windsuzu/question-answering">View Demo</a>
    ·
    <a href="https://github.com/windsuzu/question-answering/issues">Report Bug</a>
    ·
    <a href="https://github.com/windsuzu/question-answering/issues">Request Feature</a>
  </p>
</p>


<details>
<summary>Table of Contents</summary>

* [About](#about)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

</details>

---

<!-- ABOUT THE PROJECT -->
## About

<table>
<tr>
<td>

1. [BERT SQuAD Q&A pipeline](1-bert_qa_pipeline.ipynb)
Use a trained model (`deepset/bert-base-cased-squad2`) from **Huggingface Transformers** to implement Question Answering task.

2. [BERT SQuAD + Wikipedia Q&A](2-bert_qa_wiki.ipynb)
Use a trained model (`deepset/bert-base-cased-squad2`) from **Huggingface Transformers** and a document retriever from **Wikipedia** to implement open domain Q&A task.

3. [Fine Tuning My Own BERT](3-bert_qa_fine_tuning.ipynb)
Fine tune a pre-trained BERT model (`bert-base-uncased`) with SQuAD 2.0 dataset for downstream Q&A task.

<details close>
<summary>Built With</summary>
<br>

* [PyTorch](https://github.com/pytorch/pytorch)
* [HuggingFace Transformers](https://github.com/huggingface/transformers)
* [Wikipedia](https://github.com/goldsmith/Wikipedia)

</details>

</td>
</tr>
</table>

---

## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

This is an example of how to list things you need to use the software and how to install them.

1. Clone the repo
   ```sh
   git clone https://github.com/windsuzu/question-answering.git
   ```

2. Install the dependencies
   ```sh
   python -m pip install --upgrade pip

   # create a virtual environment
   python venv my-venv
   source my-venv/bin/activate   # my-venv\Scripts\activate.bat (in Windows)

   # install required modules
   python -m pip install -r requirements.txt
   ```

---

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/windsuzu/question-answering/blob/main/LICENSE) for more information.

## Contact

Reach out to the maintainer at one of the following places:

* [GitHub discussions](https://github.com/windsuzu/question-answering/discussions)
* The email which is located [in GitHub profile](https://github.com/windsuzu)

[contributors-shield]: https://img.shields.io/github/contributors/windsuzu/question-answering.svg?style=for-the-badge
[contributors-url]: https://github.com/windsuzu/question-answering/graphs/contributors
[issues-shield]: https://img.shields.io/github/issues/windsuzu/question-answering.svg?style=for-the-badge
[issues-url]: https://github.com/windsuzu/question-answering/issues
[license-shield]: https://img.shields.io/github/license/windsuzu/question-answering.svg?style=for-the-badge&label=license
[license-url]: https://github.com/windsuzu/question-answering/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/windsuzu
[pr-welcome-shield]: https://shields.io/badge/PRs-Welcome-ff69b4?style=for-the-badge
[author-shield]: https://shields.io/badge/Made_with_%E2%9D%A4_by-windsuzu-F4A92F?style=for-the-badge
[author-url]: https://github.com/windsuzu