# sharktools
tshark post processors written in perl

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++  
find-fragment-errors:
======================
Two pass tshark post-processor finds fragment processing TTL exceeded errors.  
Pass 1 finds ICMP type=11 TTL exceeded packets.  
Pass 2 finds the fragments associated with the ICMP's.  
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
