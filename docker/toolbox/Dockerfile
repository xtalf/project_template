FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd py-pip bash
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
