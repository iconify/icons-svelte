<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jyx-3ofrk"/><path class="zmj1nccll"/><path class="pcl5pkbcw"/><path class="wzsyjh0wp"/><path class="votyijv0m"/><path class="prbp3oa5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cpu-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jyx-3ofrk) {
  d: path("M13.5 5H16a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3V8l3 -3h2.5");
}

:global(.pcl5pkbcw) {
  d: path("M2 9h3");
}

:global(.prbp3oa5j) {
  d: path("M19 15h3");
}

:global(.votyijv0m) {
  d: path("M19 9h3");
}

:global(.wzsyjh0wp) {
  d: path("M2 15h3");
}

:global(.zmj1nccll) {
  d: path("M8.5 10.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
