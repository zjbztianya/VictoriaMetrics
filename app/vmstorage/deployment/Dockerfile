ARG base_image=non-existing
FROM $base_image

EXPOSE 8482
EXPOSE 8400
EXPOSE 8401

ENTRYPOINT ["/vmstorage-prod"]
ARG src_binary=non-existing
COPY $src_binary ./vmstorage-prod
