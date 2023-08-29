# Snippet Test - LG Vast
![Test Runtime]() ![GitHub contributors]()

This testing framework is a WIP for https://video-tag-builder.kargo.com and built using [Cypress](https://www.cypress.io).

## 📌 - Prerequisites
- Make sure you have [Node.js](https://nodejs.org/en/download/) installed

## 💻 - Getting Started 
- `git clone https://github.com/whitslea/snippet-test-cypress.git` OR Download folder
- `npm install`
- Make sure Cypress `e2e` folder is installed and configured via Cypress Dashboard

## 🎬 - Running Tests
- `npx cypress open` : Launches Cypress UI Dashboard to configure app and open selected test(s) - (recommended)
  * Select E2E testing to launch specs / tests
  * Select Chrome
  * Select snippets spec
  * Test runs
- `npx cypress run` : Runs all tests in headless mode within the Command Line (optional)

## ✍🏿 - Writing Tests

To add new tests, simply add test cases under cypress/e2e. See existing tests or Cypress documentation for more information.
