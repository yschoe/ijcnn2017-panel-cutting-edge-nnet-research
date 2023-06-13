# ijcnn2017-panel-cutting-edge-nnet-research
Transcript from the IJCNN 2017 panel: Cutting Edge Neural Networks Research

May 17, 2017

https://people.engr.tamu.edu/choe/choe/ijcnn2017-web/program-overview.html

IJCNN 2017 Panel: Cutting Edge Neural Networks Research

Chair:

- Asim Roy (Arizona State University)

Co-chairs: 

- Robert Kozma (University of Memphis; University of Massachusetts Amherst)
- Yoonsuck Choe (Texas A&M University)

Panelists:

- Peter Erdi (Kalamazoo College)
- Alex Graves (Google DeepMind)
- Henry Markram (Ecole polytechnique federale de Lausanne) 
- Leonid Perlovsky (Northeastern University)
- Jose Principe (University of Florida)
- Hava Siegelmann (DARPA; University of Massachusetts Amherst)

Panel Discussion Topics: The panelists were given the following list of topics for consideration.

- Perception vs. Motor function
- Information vs. Meaning
- Large vs. Scarce data
- Space vs. Time
- Degree vs. Kind
- Engineering vs. Science
- Problem solving vs. Problem posing
- Simple vs. Composite representations
- Your own question regarding:
  - Short term research
  - Long term research

1. Graves
   1. Picked “Information vs. meaning”.
   1. Compression bridges the gap between information and meaning. 
   1. Meaning requires utility, in the sense of Wittgenstein.
   1. Complexity of the body
   1. Extraction of meaning is our main task
      1. Raw data to meaning
      1. If compressed enough, can get salient meaning and structure
1. Principe
   1. Big difference between information and meaning.
   1. Meaning is how agents use it.
   1. Shannon deliberately took away meaning from information theory in order to quantify information.
   1. Information is still very powerful.
   1. To increase information, the only way is to measure it, which is kind of contrary to our experience.
1. Siegelmann
   1. [The two provide] different views.
   1. Meaning is in space time, and not in the same space [as information].
   1. Example: meaning in a medical note or X-ray: meaning relates to health/disease condition.
   1. Meaning is in a different domain: it jumps out of [its original] domain.
   1. Some doubts regarding compression -- what is to be kept after compression? Can it deal with things like episodic memory? Different memory types may exist in different spaces.
   1. Meaning is highly abstract.
1. Perlovsky
   1. Relates to physics of mind.
   1. All based on three principles
      1. Newton
      1. Mathematical model
      1. ???
   1. Must identify basic laws of the mind
      1. What are emotions?
      1. What is beauty?
      1. What is musical emotion?
      1. How these relate?
1. Q and A / Comments
   1. Compressed code still needs interpreter.
   1. Meaning is more important than information (Daniel Levine).	
      1. Encoding of information can be in two ways: (1) verbatim, (2) gist, and gist is equal to meaning. See e.g., adaptive resonance theory.
      1. Raw data cannot be dealt with -- need selective attention.
      1. Information selection is more important than information capacity.
   1. Information is related to affect-free data. Meaning is associated with reward.
   1. Meaning, grounding, and embodiment are all intertwined (Ali Minai). For example, the meaning of fire is that you get burned when you touch it.
1. Discussion following Q/A
   1. Graves
      1. Compression is a necessary condition. However, if you take away the task and the context, you’ll still get a universal representation.
   1. Siegelmann
      1. Google’s Atari Game: few bits changed and the system breaks.
   1. Perlovsky
      1. Due to Shannon, “information” now means “Shannon information”, [deprived of meaning].
1. Erdi
   1. Brief presentation based on prepared slides. See slides for details.
   1. Biological vs. artificial neural networks.
      1. Foundations: 
         1. McCulloch and Pitts model
         1. Hebbian learning
      1. LTP/LTD, backprop
      1. Synaptic plasticity: normal vs. pathological.
      1. Phenomenology can and must be discussed on the micro level.
      1. See slides for details.
1. Markram
   1. Synaptic dynamics leads to meaning
   1. Plasticity exhibits rich dynamics
   1. Rarely, algorithms adjust the dynamics itself.
   1. These dynamics may be related to information vs. meaning
   1. Bridging machine learning and neuroscience: Find biological basis of back propagation.
1. Graves
   1. In machine learning, there’s a movement to get rid of back propagation
      1. When the architecture gets deep, need to keep state info that requires a lot of information. 
      1. Short-term prediction of gradient is a possible way out.
1. Choe
   1. Plasticity: mostly discussed in the context of memory (storage of information), but we need to look into what functional changes are brought about based on plasticity (how it’s used).
1. Q and A / comments
   1. [Q] Can biologically inspired methods work in the short term and long term?
   1. Siegelmann:
      1. AI: machines that learn from experience.
      1. Current AI and ML are based on fixed data set and this is a big problem. Just like the cat that’s been trained in a carrousel with vertical stripes -- it cannot perceive the horizontal. 
      1. AI will not go forward this kind of mind set.
      1. Engineers have always gained insight from biology.
      1. Catastrophic forgetting in artificial neural networks is not a property of the biological brain. We need biological insights.
   1. Markram
      1. Difference between what should happen and what will happen
      1. Use whatever is practical (e.g., FFT vs. neural networks for speech processing)
      1. Fundamental problem:
         1. Will hit the wall in terms of generalization
         1. Need bigger and bigger data, thus the use of test set to measure generalization becomes moot.
   1. Kozma
      1. Cross-fertilization is important
   1. Minai
      1. ML has a huge problem. Training is mostly off-line. Same data are repeated. Need to look into one-shot learning.
   1. Graves
      1. ML people are well aware of these issues.
      1. Reinforcement learning: generalization becomes a whole lot more important.
         1. Very limited data
         1. Safety issue during learning
         1. All the usual assumptions [of supervised learning] are gone.
      1. Zero-shot learning
         1. Compression, representation
      1. Biological inspiration
         1. We are constantly inspired by the brain
         1. Introspection: How do “I” think? Asking this question is helpful in coming up with new ideas.
   1. Cherkassky
      1. Neural networks started with biological inspiration
      1. We don’t know anything about the brain. For example, we don’t know anything about sleep. So, this angle may have severe limitations.
      1. [It’s not real science.] Same problem with deep learning.
      1. Why not use deep statistical theories like VC theory? 
      1. Perlovsky
         1. Brain science is as much of a science than any other.
      1. Principe
         1. Engineering vs. science: Engineering is an inductive process. 
         1. Build a system and continually improve it. 
         1. It goes beyond scientific methods. It’s an alternative to science. 
         1. This also applies to ML. Differences between statistical ML and engineering ML.
         1. In engineering, we design systems around operating points and shape the envelope, as a safeguard.
         1. We can continually improve engineering systems without limit.
         1. [In the end,] we need to use both.
      1. Erdi
         1. Isn’t science basically reverse engineering? 
   1. [Q] What about higher level of reward function? Humans may do better than machines because of this.
      1. Siegelmann: Wonderful observation. Same goes for multiple tasks.
      1. Graves: 
         1. Reward and training functions are based on extrinsic and intrinsic motivations.
         1. RL will not generalize or transfer easily.
         1. Humans don’t work much based on extrinsic reward only. For example, when playing the Atari game, humans are not driven by high scores. They do it for fun and out of curiosity. DQN did well with Tetris, but some of the strategies were boring, although effective.
   1. [Q] Choe: When you compress something, doesn’t the encoded information become almost random-looking? How can the next stage cope with this? If decompression is needed, what’s the point of compressing in the first place?
      1. Graves: During training decompression is needed, but it is not needed once the representations are learned and they are used subsequently.
   1. [Q] Is autoencoder really the way to go?
      1. Graves: autoencoders are task agnostic so it is good but there are limitations. We are still hopeful that it will work well.
   1. [Q] Some biological rules are very annoying from the engineering point of view, e.g., the “Dale’s law” that basically states that neurons can be either inhibitory or excitatory, but not both. This can be a great hindrance for ANN.
      1. Markram: 
         1. Yes, that is a problem, and it is easier to solve a problem if you throw away biology. 
         1. However, such biological laws provide constraints, and this helps narrow down things, so in the long term, it may still be helpful.
         1. Also, it depends on the problem. It’s not always black or white.
   1. [Q] Neuroscience of information vs. meaning. Specialist vs. generalist. How much does multidisciplinary research pay off?
   1. [Q] What to do in the next 40 years?
   1. [Comment] Compression, meaning, and learning from experience. Autoencoders only work in domain specific ways.
1. Discussion following Q/A and Comments
   1. Markram:
      1. Need a Renaissance scientist. Must break down disciplinary boundaries.
      1. Compression: we’re throwing away redundancy and association, so we need to be careful.
      1. Tell a good story.
      1. Build a wonderful world.
      1. Find your passion.
   1. Siegelmann
      1. Use your natural talent
   1. Principe
      1. Architecture, diversity important, e.g., Neural Turing Machine.
   1. Erdi
      1. Aim to understand natural information processing systems to build the artificial.
      1. Basically what cybernetics tried to do.
   1. Perlovsky, Graves
      1. Study what you like most.


