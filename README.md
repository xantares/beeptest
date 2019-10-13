# Bats! HIIT

Bats! HIIT is a simple but useful High Intensity Interval Training timer for Android.

<a href="https://f-droid.org/packages/org.jfet.batsHIIT/" target="_blank">
<img src="https://f-droid.org/badge/get-it-on.png" alt="Get it on F-Droid" height="90"/></a>
<a href="https://play.google.com/store/apps/details?id=org.jfet.batsHIIT" target="_blank">
<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" alt="Get it on Google Play" height="90"/></a>

## How to use Bats! HIIT

### Workout structure

A HIIT workout with Bats! HIIT comprises a sequence of alternating rest (warm up/cool down) intervals and work blocks. For example, a workout with two workout blocks will look like

1. warm up
2. block #1
3. rest
4. block #2
5. cool down

Bats! HIIT always inserts rest intervals between blocks, and always includes a warm up and cool down interval.

The length of the rest interval is configurable. By default, it is 60 seconds.

### Block structure

A block is a series of work/break interval pairs; each work interval has a corresponding break interval. For example, you might configure Bats! HIIT to include 4 work intervals per block, with a 50 second work interval and 10 second break. Such a block would take 4 minutes.

### Audio and visual cues

Bats! HIIT always gives a warning consisting of 4 short chirps when you're about to transition to a new interval. Every work interval begins with a single high-pitched beep; break intervals begin with a descending, two-tone beep. Rest intervals do not have an initial beep.

During work intervals, your phone's screen will be green. In breaks, the screen will turn yellow. Rest is indicated by a red background. Your phone will also tell you how long is left in the present sub-interval and how many work/break pairs and blocks remain.

### Screen lock

When you're exercising, you want to be able to see your progress without unlocking your screen. Bats! HIIT prevents your screen from turning off, though it does allow it to dim for power savings. This lets you know at a glance how you're doing.

### Save/recall workout

You can save/recall/delete stored workouts. "Last workout" is automatically created whenever you do a workout, and is restored when the app is next started.

### Pause workout

If Bats! HIIT loses focus during a workout, your workout will be paused and will resume when Bats! HIIT resumes.

### Delay locked loop

To ensure that your workout is accurately timed, Bats! HIIT implements a feedback system called a [delay-locked loop](http://en.wikipedia.org/wiki/Delay-locked_loop). Every second, when Bats! HIIT wakes up to update the timer readout, it measures how long it was actually asleep and adjusts future delay intervals to hit the target 1-second sleep interval. In practice, this reduces short-term timing errors from more than 5% to about 0.2%; since the error is integrated over the life of your workout, the overall accuracy is two to three orders of magnitude better than the short-term errors.

## License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.
 
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Copyright (c) 2013 Riad S. Wahby <rsw@jfet.org> <kwantam@gmail.com>
