# {{cookiecutter.project_name}}
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

[![GitHub version](https://badge.fury.io/gh/conventional-changelog%2Fstandard-version.svg)](https://badge.fury.io/gh/conventional-changelog%2Fstandard-version)

##Introduction
{{cookiecutter.project_short_description}}

## Installation
1. Clone the repo
   ```sh
   git clone https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}
   ```
2. Install with pip
   ```sh
   pip install {{cookiecutter.project_slug}}
   ```
3. Install with poetry
    ```sh
    poetry install
    ```
## Testing
We currently use [Tox](https://tox.readthedocs.io/en/latest/) and [PyTest](https://docs.pytest.org/en/stable/) as the unit-testing framework to test {{cookiecutter.project_slug}}.
1. Running test with Tox
    ```sh
    tox
    ```
2. Running test with Poetry
    ```sh
    poetry run test
    ```

## Roadmap
See the [open issues](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/issues) for a list of proposed features (and known issues).

## License
Distributed under the {{cookiecutter.open_source_license}}. See `LICENSE` for more information.

## Resources
* Build, Run, Publish with [Poetry](https://python-poetry.org/)
* [Tox](https://tox.readthedocs.io/en/latest/)
* [Issue Tracker](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/issues)


[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=for-the-badge
[license-url]: https://github.com/{{cookiecutter.github_username}}/repo/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/{{cookiecutter.github_username}}
