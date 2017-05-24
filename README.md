# agent-js-jasmine
Agent for integration Jasmine + Protractor with ReportPortal.     
[ReportPortal](http://reportportal.io/)
[ReportPortal on GitHub](https://github.com/reportportal)

### How to use
1. Clone repository with agent using ```git clone```
2. Install dependencies```npm install```
3. Put your tests in the root folder.
4. Open conf.example.js and make changes:
* Write your ```token```. You can find it in your ReportPortal profile.
* Write ```YOUR PROJECT NAME```, ```YOUR LAUNCH NAME```
* Write path to your tests  ```specs: ['spec.js']```
5. Run tests  ```protractor conf.example.js```
6. Open ReportPortal, your project and launch. You should see report about tests results.


		
