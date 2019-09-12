FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello World"
LABEL "com.github.actions.description"="Write arguments to the standard output"
LABEL "com.github.actions.icon"="bell"
LABEL "com.github.actions.color"="yellow"

LABEL "repository"="https://github.com/yaroslavche/hello-github-actions"
LABEL "homepage"="https://github.com/yaroslavche/hello-github-actions"
LABEL "maintainer"="yaroslavche <yaroslav429@gmail.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
