# Speaker-Verification-using-HTK-netbeans-
A java based GUI for Speaker Recognition System using HTK.
 --First install HTK on ubuntu
 --Install Netbeans with latest Java and Scene Builder.
 -- Change the working Directory in the java codes and in the shell scripts.
 -- Train the system using the shell script training.sh.
 -- For verification, split the hmmdefs of the last mixture created into single modals.
 -- Create different test list of the Speakers to compared and find the likelihood of truespeaker-truespeaker(true score) and truespeaker-  falsespeaker(false score).
-- Find the threshold likelihood and find the Equal Error Rate(EER).
 -- test_script.sh for identification
 -- testfinal.sh for verification(after finding the threshold).
 -- Record the Audio in wav format.Use silenceremoval.sh to remove end silence.