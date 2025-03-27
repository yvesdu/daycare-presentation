---
# You can also start simply with 'default'
theme: seriph
# use the uploaded image as background instead of random Unsplash image
background: './daycare14.jpg'
backgroundSize: cover
# some information about your slides (markdown enabled)
title: GetDaycare.space – Making Childcare Affordable & Accessible in Canada
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
highlighter: shiki
lineNumbers: false
css: unocss
themeConfig:
  primary: '#2B90B6'
layout: cover
---

# GetDaycare.space
## Making Childcare Affordable & Accessible in Canada

<div class="pt-12">
  <span class="px-4 py-2 rounded cursor-pointer text-xl bg-white bg-opacity-80 text-gray-800" hover="bg-white bg-opacity-90">
    Connecting families with trusted childcare providers in Ottawa
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://getdaycare.space" target="_blank" alt="Website"
    class="text-xl slidev-icon-btn opacity-70 !border-none !hover:text-white">
    <carbon:globe />
  </a>
</div>

<style>
.slidev-layout {
  background-color: transparent;
  position: relative;
}

.slidev-layout::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.3);
  z-index: -1;
}

h1 {
  color: white;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
}

h2 {
  color: white;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
}
</style>

<!--
Opening slide: Emphasize the transformative nature of our platform
Highlight the immediate value proposition for both parents and providers
-->

---
layout: default
class: px-4 py-4
---

# The Problem {class="text-4xl font-bold text-gray-800"}

<div class="grid grid-cols-3 gap-4 mt-2">
<div v-click class="flex flex-col p-3 rounded-lg bg-red-100 border border-red-300">
  <div class="flex items-center gap-2 mb-1">
    <div class="p-1.5 bg-red-200 rounded-full">
      <carbon:warning-alt class="text-red-700 text-base" />
    </div>
    <span class="text-base font-bold text-red-700">Financial Burden</span>
  </div>
  <p class="text-gray-700 text-sm mt-1">Parents spend up to <span class="text-red-700 font-bold text-lg">33%</span> of income on childcare — more than housing!</p>
</div>

<div v-click class="flex flex-col p-3 rounded-lg bg-blue-100 border border-blue-300">
  <div class="flex items-center gap-2 mb-1">
    <div class="p-1.5 bg-blue-200 rounded-full">
      <carbon:time class="text-blue-700 text-base" />
    </div>
    <span class="text-base font-bold text-blue-700">System Challenges</span>
  </div>
  <p class="text-gray-700 mb-1 text-sm">Finding reliable care is a nightmare:</p>
  <ul class="list-disc ml-4 text-gray-700 space-y-0.5 text-xs">
    <li>Fragmented information across platforms</li>
    <li>Endless waitlists with no visibility</li>
    <li>No standardized quality metrics</li>
  </ul>
</div>

<div v-click class="flex flex-col p-3 rounded-lg bg-green-100 border border-green-300">
  <div class="flex items-center gap-2 mb-1">
    <div class="p-1.5 bg-green-200 rounded-full">
      <carbon:search class="text-green-700 text-base" />
    </div>
    <span class="text-base font-bold text-green-700">Broken System</span>
  </div>
  <p class="text-gray-700 text-sm mt-1">Canadian families are struggling to find affordable, high-quality childcare options</p>
</div>
</div>

<div class="grid grid-cols-1 gap-3 mt-3">
<div class="col-span-1">
  <div v-click class="flex flex-col p-3 rounded-lg bg-purple-100 border border-purple-300">
    <div class="flex items-center gap-2 mb-2">
      <div class="p-1.5 bg-purple-200 rounded-full">
        <carbon:chart-line class="text-purple-700 text-base" />
      </div>
      <span class="text-base font-bold text-purple-700">Market Demand</span>
    </div>
    <div class="grid grid-cols-2 gap-4">
      <div>
        <p class="text-gray-700 text-sm mb-1">Key Statistics:</p>
        <ul class="list-disc ml-4 text-gray-700 space-y-0.5 text-xs">
          <li>Over 54% of parents struggle to find care</li>
          <li>Waitlists exceed 2+ years in major cities</li>
          <li>Childcare costs rising faster than inflation</li>
        </ul>
      </div>
      <div>
        <p class="text-gray-700 text-sm mb-1">Parents Want:</p>
        <ul class="list-disc ml-4 text-gray-700 space-y-0.5 text-xs">
          <li>Transparent pricing & availability</li>
          <li>Quality assurance & standards</li>
          <li>Simplified application process</li>
        </ul>
      </div>
    </div>
  </div>
</div>
</div>

<div class="absolute bottom-4 w-full left-0 px-4">
  <div v-click class="flex justify-center">
    <div class="px-4 py-1.5 bg-gray-100 rounded-full border border-gray-300">
      <span class="text-sm font-bold text-gray-700">Finding a solution to the childcare crisis in Canada</span>
    </div>
  </div>
</div>

<!--
Key pain points that resonate with parents
Emphasize the financial burden
Highlight the systemic issues
-->

---
layout: fact
class: text-center
---

# The Solution {class="text-4xl font-bold text-gray-800"}

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="flex flex-col h-full">
  <div class="bg-blue-50 p-6 rounded-lg border border-blue-200 h-full flex flex-col">
    <div class="flex items-center gap-3 mb-4">
      <div class="w-12 h-12 rounded-full bg-blue-100 flex items-center justify-center">
        <div class="text-2xl">🎯</div>
      </div>
      <h3 class="text-xl font-bold text-blue-700">User-friendly Platform</h3>
    </div>
    <ul class="space-y-3 text-left flex-grow">
      <li class="flex items-start gap-2">
        <div class="w-5 h-5 rounded-full bg-blue-100 flex items-center justify-center mt-0.5">
          <carbon:checkmark class="text-blue-700 text-xs" />
        </div>
        <span class="text-gray-700">Match parents with verified providers</span>
      </li>
      <li class="flex items-start gap-2">
        <div class="w-5 h-5 rounded-full bg-blue-100 flex items-center justify-center mt-0.5">
          <carbon:checkmark class="text-blue-700 text-xs" />
        </div>
        <span class="text-gray-700">Real-time availability tracking</span>
      </li>
      <li class="flex items-start gap-2">
        <div class="w-5 h-5 rounded-full bg-blue-100 flex items-center justify-center mt-0.5">
          <carbon:checkmark class="text-blue-700 text-xs" />
        </div>
        <span class="text-gray-700">Quality assessment system</span>
      </li>
    </ul>
  </div>
</div>

<div v-click class="flex flex-col h-full">
  <div class="bg-green-50 p-6 rounded-lg border border-green-200 h-full flex flex-col">
    <div class="flex items-center gap-3 mb-4">
      <div class="w-12 h-12 rounded-full bg-green-100 flex items-center justify-center">
        <div class="text-2xl">📊</div>
      </div>
      <h3 class="text-xl font-bold text-green-700">Data-Driven Insights</h3>
    </div>
    <ul class="space-y-3 text-left flex-grow">
      <li class="flex items-start gap-2">
        <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center mt-0.5">
          <carbon:checkmark class="text-green-700 text-xs" />
        </div>
        <span class="text-gray-700">Transparent parent reviews</span>
      </li>
      <li class="flex items-start gap-2">
        <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center mt-0.5">
          <carbon:checkmark class="text-green-700 text-xs" />
        </div>
        <span class="text-gray-700">Up-to-date availability</span>
      </li>
      <li class="flex items-start gap-2">
        <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center mt-0.5">
          <carbon:checkmark class="text-green-700 text-xs" />
        </div>
        <span class="text-gray-700">Provider comparisons</span>
      </li>
    </ul>
  </div>
</div>

<div v-click class="flex flex-col h-full">
  <div class="bg-purple-50 p-6 rounded-lg border border-purple-200 h-full flex flex-col">
    <div class="flex items-center gap-3 mb-4">
      <div class="w-12 h-12 rounded-full bg-purple-100 flex items-center justify-center">
        <div class="text-2xl">🌐</div>
      </div>
      <h3 class="text-xl font-bold text-purple-700">Complete Childcare Hub</h3>
    </div>
    <ul class="space-y-3 text-left flex-grow">
      <li class="flex items-start gap-2">
        <div class="w-5 h-5 rounded-full bg-purple-100 flex items-center justify-center mt-0.5">
          <carbon:checkmark class="text-purple-700 text-xs" />
        </div>
        <span class="text-gray-700">Licensed daycare providers</span>
      </li>
      <li class="flex items-start gap-2">
        <div class="w-5 h-5 rounded-full bg-purple-100 flex items-center justify-center mt-0.5">
          <carbon:checkmark class="text-purple-700 text-xs" />
        </div>
        <span class="text-gray-700">Camps & seasonal programs</span>
      </li>
      <li class="flex items-start gap-2">
        <div class="w-5 h-5 rounded-full bg-purple-100 flex items-center justify-center mt-0.5">
          <carbon:checkmark class="text-purple-700 text-xs" />
        </div>
        <span class="text-gray-700">After-school & extended care</span>
      </li>
    </ul>
  </div>
</div>
</div>

<div v-click class="mt-12 text-center">
  <div class="inline-block px-6 py-3 bg-gray-100 rounded-full border border-gray-300">
    <span class="text-xl font-bold text-gray-700">One platform for all your childcare needs</span>
  </div>
</div>

---
layout: fact
---

# Market Opportunity {class="text-4xl font-bold text-gray-800"}

<div class="grid grid-cols-3 gap-8 mt-8">
<div v-click class="text-center">
  <div class="text-3xl font-bold text-blue-600">$30B</div>
  <div class="text-sm text-gray-600">Federal Investment</div>
</div>

<div v-click class="text-center">
  <div class="text-3xl font-bold text-green-600">250K</div>
  <div class="text-sm text-gray-600">New Childcare Spaces</div>
</div>

<div v-click class="text-center">
  <div class="text-3xl font-bold text-purple-600">1.6M</div>
  <div class="text-sm text-gray-600">Canadian Families Need Care</div>
</div>
</div>

<div class="text-center mt-12 text-xl">
  <div v-click>By 2026, costs will drop to <span class="text-green-600 font-bold">$10/day</span></div>
  <div v-click class="mt-4 text-gray-600">Creating unprecedented demand for providers & better access</div>
</div>

<!--
Emphasize the massive market potential
Highlight government support and policy changes
-->

---
layout: two-cols
---

# What Sets Us Apart

<v-clicks>

- 🚀 **Real-time Platform**
  Not just a directory - live updates & booking

- 📊 **Data-Driven**
  Making informed decisions easier

- 🔄 **Scalable Solution**
  Adaptable to various childcare needs

- 🤝 **CWELCC Support**
  Supporting Ontario's accountability goals

</v-clicks>

::right::

<div class="ml-4">
<div class="mt-4">
  <h3 class="font-bold mb-2">Comparison</h3>
  <table class="text-sm">
    <tr>
      <th class="text-left p-2">Feature</th>
      <th class="text-center p-2">Us</th>
      <th class="text-center p-2">Facebook Groups</th>
      <th class="text-center p-2">Gov Sites</th>
    </tr>
    <tr v-click>
      <td class="p-2">Real-time Updates</td>
      <td class="text-center">✅</td>
      <td class="text-center">❌</td>
      <td class="text-center">❌</td>
    </tr>
    <tr v-click>
      <td class="p-2">Verified Reviews</td>
      <td class="text-center">✅</td>
      <td class="text-center">❌</td>
      <td class="text-center">❌</td>
    </tr>
    <tr v-click>
      <td class="p-2">Booking System</td>
      <td class="text-center">✅</td>
      <td class="text-center">❌</td>
      <td class="text-center">❌</td>
    </tr>
    <tr v-click>
      <td class="p-2">Quality Metrics</td>
      <td class="text-center">✅</td>
      <td class="text-center">❌</td>
      <td class="text-center">❌</td>
    </tr>
  </table>
</div>
</div>

---
layout: section
---

# Current Progress & Vision

<div class="grid grid-cols-2 gap-12 mt-8">
<div v-click class="p-6 rounded-lg border border-gray-200 bg-opacity-10 bg-white">
  <h3 class="font-bold text-2xl mb-6 flex items-center gap-2">
    <div class="text-green-500">✅</div>
    Current Progress
  </h3>
  <ul class="space-y-4">
    <li class="flex items-center gap-3">
      <div class="text-blue-500 text-xl">🚀</div>
      <div>
        <div class="font-semibold">Web App Launch</div>
        <div class="opacity-75 text-sm">Successfully deployed in Ottawa</div>
      </div>
    </li>
    <li class="flex items-center gap-3">
      <div class="text-green-500 text-xl">🧪</div>
      <div>
        <div class="font-semibold">User Testing</div>
        <div class="opacity-75 text-sm">Initial testing phase completed</div>
      </div>
    </li>
    <li class="flex items-center gap-3">
      <div class="text-purple-500 text-xl">🤝</div>
      <div>
        <div class="font-semibold">Provider Engagement</div>
        <div class="opacity-75 text-sm">Early adopters onboarded</div>
      </div>
    </li>
    <li class="flex items-center gap-3">
      <div class="text-yellow-500 text-xl">⭐</div>
      <div>
        <div class="font-semibold">User Feedback</div>
        <div class="opacity-75 text-sm">Positive response from community</div>
      </div>
    </li>
  </ul>
</div>

<div v-click class="p-6 rounded-lg border border-gray-200 bg-opacity-10 bg-white">
  <h3 class="font-bold text-2xl mb-6 flex items-center gap-2">
    <div class="text-blue-500">🎯</div>
    Next Steps
  </h3>
  <ul class="space-y-4">
    <li class="flex items-center gap-3">
      <div class="text-orange-500 text-xl">🏕️</div>
      <div>
        <div class="font-semibold">Service Expansion</div>
        <div class="opacity-75 text-sm">Adding camps & activities</div>
      </div>
    </li>
    <li class="flex items-center gap-3">
      <div class="text-green-500 text-xl">📈</div>
      <div>
        <div class="font-semibold">Growth Strategy</div>
        <div class="opacity-75 text-sm">Accelerating user adoption</div>
      </div>
    </li>
    <li class="flex items-center gap-3">
      <div class="text-blue-500 text-xl">🔄</div>
      <div>
        <div class="font-semibold">Integration</div>
        <div class="opacity-75 text-sm">Partnering with providers</div>
      </div>
    </li>
    <li class="flex items-center gap-3">
      <div class="text-red-500 text-xl">🍁</div>
      <div>
        <div class="font-semibold">National Expansion</div>
        <div class="opacity-75 text-sm">Scaling across Canada</div>
      </div>
    </li>
  </ul>
</div>
</div>

<div v-click class="mt-12 p-6 rounded-lg border border-gray-200 bg-opacity-10 bg-white">
  <h3 class="font-bold text-2xl mb-4 text-center">Our Vision</h3>
  <div class="text-xl text-center">Become Canada's #1 trusted childcare platform</div>
  <div class="mt-4 text-center opacity-75">
    Supporting a <span class="text-green-500 font-bold">$3.86B</span> industry with real-time insights & transparency
  </div>
</div>

---
layout: center
class: text-center
---

# Our Roadmap {class="text-4xl font-bold text-gray-800"}
## Next 12 Months {class="text-2xl text-gray-600 mt-2"}

<div class="grid grid-cols-3 gap-8 mt-12">
<div v-click class="flex flex-col items-center">
  <div class="w-16 h-16 rounded-full bg-blue-100 flex items-center justify-center mb-4 border border-blue-200">
    <div class="text-2xl">🎯</div>
  </div>
  <h3 class="font-bold text-xl mb-4 text-blue-700">Product-Market Fit</h3>
  <ul class="text-left space-y-2 text-gray-700">
    <li class="flex items-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-blue-600"></div>
      Enhance user experience
    </li>
    <li class="flex items-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-blue-600"></div>
      Implement feedback
    </li>
    <li class="flex items-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-blue-600"></div>
      Refine algorithms
    </li>
  </ul>
</div>

<div v-click class="flex flex-col items-center">
  <div class="w-16 h-16 rounded-full bg-green-100 flex items-center justify-center mb-4 border border-green-200">
    <div class="text-2xl">📈</div>
  </div>
  <h3 class="font-bold text-xl mb-4 text-green-700">User Growth</h3>
  <ul class="text-left space-y-2 text-gray-700">
    <li class="flex items-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-green-600"></div>
      Expand beyond Ottawa
    </li>
    <li class="flex items-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-green-600"></div>
      Onboard providers
    </li>
    <li class="flex items-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-green-600"></div>
      Build partnerships
    </li>
  </ul>
</div>

<div v-click class="flex flex-col items-center">
  <div class="w-16 h-16 rounded-full bg-purple-100 flex items-center justify-center mb-4 border border-purple-200">
    <div class="text-2xl">⚡</div>
  </div>
  <h3 class="font-bold text-xl mb-4 text-purple-700">Platform Development</h3>
  <ul class="text-left space-y-2 text-gray-700">
    <li class="flex items-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-purple-600"></div>
      Real-time tracking
    </li>
    <li class="flex items-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-purple-600"></div>
      Smart booking
    </li>
    <li class="flex items-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-purple-600"></div>
      Provider integration
    </li>
  </ul>
</div>
</div>

<div v-click class="mt-12 text-center">
  <div class="inline-block px-6 py-3 bg-gray-100 rounded-full border border-gray-300">
    <span class="text-xl text-gray-700">Building the future of childcare access in Canada</span>
  </div>
</div>

---
layout: fact
---

# The Ask {class="text-4xl font-bold text-gray-800"}

<div class="grid grid-cols-2 gap-12 mt-8">
<div v-click>
  <h3 class="font-bold text-2xl mb-4 flex items-center gap-2">
    <div class="text-yellow-600">💰</div> Seed Funding: $200K
  </h3>
  <div class="pl-4 space-y-3">
    <div class="flex items-center gap-3 bg-blue-50 p-3 rounded-lg border border-blue-200">
      <div class="w-8 h-8 rounded-full bg-blue-100 flex items-center justify-center">
        <carbon:application-web class="text-blue-700" />
      </div>
      <div>
        <div class="font-semibold text-gray-800">Tech Development</div>
        <div class="text-sm text-gray-600">40% · Platform enhancements</div>
      </div>
    </div>
    <div class="flex items-center gap-3 bg-green-50 p-3 rounded-lg border border-green-200">
      <div class="w-8 h-8 rounded-full bg-green-100 flex items-center justify-center">
        <carbon:chart-line class="text-green-700" />
      </div>
      <div>
        <div class="font-semibold text-gray-800">Marketing & Growth</div>
        <div class="text-sm text-gray-600">40% · User acquisition</div>
      </div>
    </div>
    <div class="flex items-center gap-3 bg-purple-50 p-3 rounded-lg border border-purple-200">
      <div class="w-8 h-8 rounded-full bg-purple-100 flex items-center justify-center">
        <carbon:enterprise class="text-purple-700" />
      </div>
      <div>
        <div class="font-semibold text-gray-800">Operations</div>
        <div class="text-sm text-gray-600">20% · Team & partnerships</div>
      </div>
    </div>
  </div>
</div>

<div v-click>
  <h3 class="font-bold text-2xl mb-4 flex items-center gap-2">
    <div class="text-blue-700">🤝</div> How You Can Help
  </h3>
  <div class="pl-4 space-y-3">
    <div class="flex items-center gap-3 bg-cyan-50 p-3 rounded-lg border border-cyan-200">
      <div class="w-8 h-8 rounded-full bg-cyan-100 flex items-center justify-center">
        <carbon:network-4 class="text-cyan-700" />
      </div>
      <div>
        <div class="font-semibold text-gray-800">Network Support</div>
        <div class="text-sm text-gray-600">Introductions to investors & partners</div>
      </div>
    </div>
    <div class="flex items-center gap-3 bg-orange-50 p-3 rounded-lg border border-orange-200">
      <div class="w-8 h-8 rounded-full bg-orange-100 flex items-center justify-center">
        <carbon:share-knowledge class="text-orange-700" />
      </div>
      <div>
        <div class="font-semibold text-gray-800">Community Awareness</div>
        <div class="text-sm text-gray-600">Spread the word to parents & providers</div>
      </div>
    </div>
    <div class="flex items-center gap-3 bg-indigo-50 p-3 rounded-lg border border-indigo-200">
      <div class="w-8 h-8 rounded-full bg-indigo-100 flex items-center justify-center">
        <carbon:idea class="text-indigo-700" />
      </div>
      <div>
        <div class="font-semibold text-gray-800">Strategic Feedback</div>
        <div class="text-sm text-gray-600">Insights to improve our platform</div>
      </div>
    </div>
    <div class="flex items-center gap-3 bg-pink-50 p-3 rounded-lg border border-pink-200">
      <div class="w-8 h-8 rounded-full bg-pink-100 flex items-center justify-center">
        <carbon:partnership class="text-pink-700" />
      </div>
      <div>
        <div class="font-semibold text-gray-800">Provider Introductions</div>
        <div class="text-sm text-gray-600">Connect us with childcare providers</div>
      </div>
    </div>
  </div>
</div>
</div>

<div v-click class="text-center mt-12">
  <div class="inline-block px-6 py-3 bg-gray-100 rounded-full border border-gray-300">
    <span class="text-xl font-bold text-gray-700">Join us in fixing Canada's childcare crisis!</span>
  </div>
</div>

---
layout: end
---

# Thank You

[getdaycare.space](https://getdaycare.space) · Making childcare accessible for all

<div class="pt-4 opacity-75">
  <div class="mb-2">Patrick Ngenzi<br>JPNgenzi@gmail.com</div>
  <div>Yves Dusenge<br>dusengeyves@gmail.com</div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Final call to action
Emphasize the opportunity to be part of the solution
-->
