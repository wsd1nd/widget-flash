# Flash Widget

**UPDATE:** This widget will no longer be supported. 

## Introduction

The Flash Widget allows you to display one Flash file in a Presentation. The Flash file must be accessible from a URL and only the SWF file format is supported.

You can store your SWF File in the Media Library by adding a Video or Image Item to your Placeholder, uploading the SWF File to the Media Library, and then copying the URL to use in the Flash Widget.

The Widget proportionally sizes the Flash file to the size of the Placeholder it has been added to. Do not use very large or high resolution files that must be significantly reduced as it can lead to unsatisfactory results.

Flash Widget works in conjunction with [Rise Vision](http://www.risevision.com), the [digital signage management application](http://rva.risevision.com/) that runs on [Google Cloud](https://cloud.google.com).

At this time Chrome is the only browser that this project and Rise Vision supports.

## Development

### Dependencies
* [Git](http://git-scm.com/) - Git is a free and open source distributed version control system that is used to manage our source code on Github.

### Local Development Environment Setup and Installation
To make changes to the Widget, you'll first need to install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

The Widget can now be installed by executing the following command in Terminal:
```
git clone https://github.com/Rise-Vision/widget-flash.git
```

### Deployment
Once you are satisifed with your changes, deploy them to your server. In the Rise Vision Platform, you can then add your custom Widget via the *Gadgets* tab. Give your Widget a name, select a *Type* of *Widget*, paste the link to the `flash.html` file in the *URL* field, and the link to the `settings.html` file in the *Custom UI URL* field:

![Add a Widget](https://cloud.githubusercontent.com/assets/1190420/5113377/2f2d9240-6ffd-11e4-98ad-a484c1fa7183.png)


## Submitting Issues
If you encounter problems or find defects we really want to hear about them. If you could take the time to add them as issues to this Repository it would be most appreciated. When reporting issues please use the following format where applicable:

**Reproduction Steps**

1. did this
2. then that
3. followed by this (screenshots / video captures always help)

**Expected Results**

What you expected to happen.

**Actual Results**

What actually happened. (screenshots / video captures always help)

### Languages
If you would like translate the user interface for this product to another language please complete the following:
- Download the english translation file from this repository.
- Download and install POEdit. This is software that you can use to write translations into another language.
- Open the translation file in the [POEdit](http://www.poedit.net/) program and set the language for which you are writing a translation.
- In the Source text window, you will see the English word or phrase to be translated. You can provide a translation for it in the Translation window.
- When the translation is complete, save it with a .po extension and email the file to support@risevision.com. Please be sure to indicate the Widget or app the translation file is for, as well as the language that it has been translated into, and we will integrate it after the translation has been verified.

## Resources
If you have any questions or problems please don't hesitate to join our lively and responsive community at http://community.risevision.com.

If you are looking for user documentation on Rise Vision please see http://www.risevision.com/help/users/

If you would like more information on developing applications for Rise Vision please visit http://www.risevision.com/help/developers/.

**Facilitator**

[Stuart Lees](https://github.com/stulees "Stuart Lees")