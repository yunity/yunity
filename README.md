[![Stories in "Tasking"](https://badge.waffle.io/yunity/yunity.svg?label=%5Bkanban%5D%20tasking&title=Tasking)](https://waffle.io/yunity/yunity)
[![Stories in "Next"](https://badge.waffle.io/yunity/yunity.svg?label=%5Bkanban%5D%20next&title=Next)](https://waffle.io/yunity/yunity)
[![Stories in "In Progress"](https://badge.waffle.io/yunity/yunity.svg?label=%5Bkanban%5D%20in-progress&title=In%20Progress)](https://waffle.io/yunity/yunity)

# yunity

Meta repo, used to:
- record issues that are not specific to one repo - https://github.com/yunity/yunity/issues
- have a main repo to attach our waffle board to - https://waffle.io/yunity/yunity

No code here please :)
## yunity setup
This provides scripts to get th app up and running. The primary purpose is for
developers to  get up and running easily.
Please create an issue if this doesn't work out of the box for you, it's a work in progress :)

It helps you to:

- understand how to install system dependencies (information only)
- clone the seperate repos
- setup the application dependencies
- setup the database and run the migrations
- run/manage the application's processes using pm2

The app is split into frontend and backend parts. You can either:

- run everything locally on your machine
- run the backend in a vagrant vm and run the frontend locally (Note: the app is  in heavy development right now, so this might not work)

### System and Application setup
  Please follow our wiki's detailed instructions for [System Setup](https://yunity.atlassian.net/wiki/display/YUN/System+Setup)
  and [Application Setup](https://yunity.atlassian.net/wiki/display/YUN/Application+Setup)

### More information
  You can also have a look into our wiki's [Development Team](https://yunity.atlassian.net/wiki/display/YUN/Development+Team)
  to discover more information

## Thanks

We would like to thank the following generous sponsors who provide us with licenses to use their lovely software. If you are a yunity developer and would like a license, please ask in the #development slack channel.

### BrowserStack

![browser stack logo](https://dgzoq9b5asjg1.cloudfront.net/production/images/static/header/header-logo.svg?1459235958)

_Live, Web-Based Browser Testing, Instant access to all real mobile and desktop browsers. Say goodbye to your lab of devices and virtual machines._

https://www.browserstack.com/

This lets us run our automated frontend karma tests on real browsers.

### JetBrains PyCharm

![pycharm logo](http://blog.jetbrains.com/pycharm/files/2015/12/PyCharm_400x400_Twitter_logo_white.png)

_Python IDE for Professional Developers_

They provide us with a license for the professional edition, which gives integrated django support (and some other stuff too I imagine).

https://www.jetbrains.com/pycharm/
