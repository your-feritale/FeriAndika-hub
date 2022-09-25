### Hi there <h1>Hi there! <span class="wave">👋</span></h1>
#### My name is Feri Andika
- 🔭 I’m currently studying in Bunda Mulia University
- 🌱 I’m currently learning Data Science 
- 🤔 I’m looking for help with machine learning
- 📫 How to reach me: Instagram @it.s_ferified
- 😄 Pronouns: He / His
- ⚡ Fun fact: I am me
-->

.wave {
  animation-name: wave-animation;  /* Refers to the name of your @keyframes element below */
  animation-duration: 2.5s;        /* Change to speed up or slow down */
  animation-iteration-count: infinite;  /* Never stop waving :) */
  transform-origin: 70% 70%;       /* Pivot around the bottom-left palm */
  display: inline-block;
}

@keyframes wave-animation {
    0% { transform: rotate( 0.0deg) }
   10% { transform: rotate(14.0deg) }  /* The following five values can be played with to make the waving more or less extreme */
   20% { transform: rotate(-8.0deg) }
   30% { transform: rotate(14.0deg) }
   40% { transform: rotate(-4.0deg) }
   50% { transform: rotate(10.0deg) }
   60% { transform: rotate( 0.0deg) }  /* Reset for the last half to pause */
  100% { transform: rotate( 0.0deg) }
}
