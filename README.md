# aap_upgrade


wget --save-cookies cookies.txt \
     --keep-session-cookies \
     --post-data "username=YOUR_RH_USERNAME&password=YOUR_RH_PASSWORD" \
     https://access.redhat.com/login

     
wget --load-cookies cookies.txt \
https://access.redhat.com/downloads/content/480/ver=/rhel---9/2.6/x86_64/product-software


curl.exe -c cookies.txt `
  -d "username=YOUR_RH_USERNAME&password=YOUR_RH_PASSWORD" `
  https://access.redhat.com/login

