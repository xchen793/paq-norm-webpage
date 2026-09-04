Drop your recorded narration files into this folder using these exact filenames
so they line up with the <audio> tags already in index.html:

  overview.mp3       -> plays at the end of the Abstract section
  problem.mp3         -> plays at the end of "The 2AFC task, and why a fixed interval isn't fair"
  observation.mp3    -> plays at the end of "Observation: JNDs are not constant across the population"
  method.mp3           -> plays at the end of the Method section (all 3 steps)
  results.mp3          -> plays at the end of the Results section
  limitations.mp3     -> plays at the end of the Limitations section

Format: .mp3 is assumed (audio/mpeg). If you record in a different format
(e.g. .wav or .m4a), either convert to .mp3 first, or update the corresponding
<source src="..." type="..."> line in index.html to match.

Once a file with the matching name is placed here, its player will work
automatically — no other changes needed.
