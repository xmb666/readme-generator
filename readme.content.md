## Usage

### Create README configuration file
README.md generator needs a configuration file of your README, just create a file called <a href="https://github.com/ppizarror/readme-generator/blob/master/readme.json">readme.json</a> in the root of your repository:

```json
{
  "PROJECT": {
    "NAME": "",
    "ICON": {
      "IMAGE": "",
      "ALT": "",
      "WIDTH": 0,
      "HEIGHT": 0
    },
    "URL": "",
    "URL_TITLE": ""
  },
  "AUTHOR": {
    "NAME": "",
    "URL": "",
    "ALT": "",
    "DATE": "",
    "SECTION": {
      "TITLE": "Author",
      "SHOW": true
    }
  },
  "DESCRIPTION": "",
  "BADGES": {
    "0": {
      "IMAGE": "",
      "HREF": "",
      "ALT": ""
    },
    "1": {
      "IMAGE": "",
      "HREF": "",
      "ALT": ""
    },
    "2": {
      "NEWLINE": true
    },
    "3": {
      "IMAGE": "",
      "HREF": "",
      "ALT": ""
    }
  },
  "CONTENT": "readme.content.md"
}
```

In <a href="https://github.com/ppizarror/readme-generator/blob/master/readme.content.md">readme.content.md</a> you can write the main content of your README, this has to be in the same root of your <a href="https://github.com/ppizarror/readme-generator/blob/master/readme.json">readme.json</a> configuration.

<details>
<summary>Example of this README</summary>

```json
{
  "PROJECT": {
    "NAME": "README.md Generator",
    "ICON": {
      "IMAGE": "icon.png",
      "ALT": "",
      "WIDTH": 200,
      "HEIGHT": 200
    },
    "URL": "https://ppizarror.com/readme-generator/",
    "URL_TITLE": "README.md Generator"
  },
  "AUTHOR": {
    "NAME": "Pablo Pizarro R.",
    "URL": "https://ppizarror.com",
    "ALT": "ppizarror",
    "DATE": "2017",
    "SECTION": {
      "TITLE": "Author",
      "SHOW": true
    }
  },
  "DESCRIPTION": "Generate a README.md file from a configuration file",
  "BADGES": {
    "0": {
      "IMAGE": "https://ppizarror.com/badges/author.svg",
      "HREF": "https://ppizarror.com",
      "ALT": "@ppizarror"
    },
    "1": {
      "IMAGE": "https://ppizarror.com/badges/licensemit.svg",
      "HREF": "https://opensource.org/licenses/MIT/",
      "ALT": "MIT License"
    },
    "2": {
      "IMAGE": "https://ppizarror.com/badges/python27.svg",
      "HREF": "https://www.python.org/downloads/",
      "ALT": "Python 2.7"
    }
  },
  "CONTENT": "readme.content.md"
}
```

</details><br>

### Run README Generator
<p align="center">
  <img src="https://ppizarror.com/resources/images/readme-generator/app.PNG" width="40%" />
</p>

Just run this Python app, load your file and click on ```Generate README.md``` button to create your new README file. You can also push your new readme to your github account by clicking on the icon next to the button.

## License
This project is under MIT License [https://opensource.org/licenses/MIT]