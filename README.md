# chat-app

## Build a live chat application using Ember.js and Pusher
This project contains the source code for a very simple realtime chat application with sentiment analysis. With sentiment analysis, we are able to detect the mood of a person based on the words they use in their chat messages.

[View tutorial](https://pusher.com/tutorials/chat-app-emberjs)

Here is a screenshot of the application.


![updated-chat](https://user-images.githubusercontent.com/19610753/41297385-ea1edcca-6e56-11e8-81e2-7a63f6d85cbd.gif)


## Prerequisites
1. You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

2. Create a Pusher application - Create a new application on your Pusher Dashboard to get your app credentials.

## Getting Started

### Clone the repository
```bash
$ git clone https://github.com/yemiwebby/chat-app-ember.git
```

### Change directory
```bash
$ cd chat-app-ember
```

### Run the application
```bash
$ ember serve
```

* Visit your app at [http://localhost:4200](http://localhost:4200).

## Built With

* [Emberjs](https://www.emberjs.com/) - A productive frontend framework built for ambitious web developers.

* [Pusher](https://pusher.com/) - A Node.js client to interact with the Pusher REST API

* [Sentiment](https://github.com/thisandagain/sentiment)- Sentiment is a module that uses the AFINN-165 wordlist and Emoji Sentiment Ranking to perform sentiment analysis on arbitrary blocks of input text.


### Building

* `ember build` (development)
* `ember build --environment production` (production)