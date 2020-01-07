FROM nginx:1.16-alpine

RUN rm /etc/nginx/conf.d/default.conf

COPY /var/www/.docker/nginx/nginx.conf /etc/nginx/conf.d
