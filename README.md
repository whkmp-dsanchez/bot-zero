# bot-zero
<a href="https://hubot.github.com/">Hubot</a> is a fantastic project that enabled us to build great bots. The **bot-zero** project aims to give you a cleaned up version with some examples that run on ES6 (instead of Coffee-script).

[![Build Status](https://travis-ci.org/wehkamp/bot-zero.svg?branch=master)](https://travis-ci.org/wehkamp/bot-zero)
[![forever](https://david-dm.org/wehkamp/bot-zero.svg)](https://david-dm.org/wehkamp/bot-zero)
[![coding style: JavaScript Standard Style)](https://img.shields.io/badge/code%20style-JavaScript%20Standard%20Style-ff69b4.svg)](https://standardjs.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Getting started
Starting this project is really easy:

1. Fork this project (top right corner)
2. Clone your forked project to your pc.
3. Goto http://slackapi.github.io/hubot-slack/#getting-a-slack-token to read up on how to get a Slack token for your bot.
4. Add the token to your environment.
5. Open a terminal and navigate to your bot directory.
6. Enter `npm install` to install the NodeJs packages.
7. Start the bot using `npm start`.
7. Enjoy!

## Good to know

**Packages** <br/>
We've included some packages:
- `axios`: a promise-based HTTP client. Makes it easier to use promises of your HTTP requests.
- `dotenv`: allows you to store environment variables in the .env file in the root of the project.
- `hubot-command-mapper`: allows for the mapping of commands with parameters to the Hubot without the need for regular expressions. 

**NPM**<br/>
Use NPM to interact with the bot:
- `npm start` will start the bot.
- `npm test` will kick of the tests of the bot. They are located in the `tests` directory. Testing is done using <a href="https://www.npmjs.com/package/hubot-pretend">Hubot Pretend</a>. It'll also tests against <a href="https://standardjs.com/">JavaScript Standard Style</a> to make sure your coding is consistent.

**Clean up**<br/>
The bot was generated using the <a href="http://slackapi.github.io/hubot-slack/">Slack Developer Kit for Hubot</a>. It was "cleaned" using a script from <a href="https://keestalkstech.com/2018/04/cleaning-up-the-default-hubot-installation/">Cleaning up the Default Hubot Installation</a>.

## Tech
We're using the following stack:
- [x] NodeJs
- [x] ES6
- [x] Hubot
- [x] NPM
