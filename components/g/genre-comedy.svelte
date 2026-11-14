<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vnoccubap"/><path class="r4vo9w49q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:genre-comedy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r4vo9w49q) {
  d: path("M6.5 9.5a2 2 0 0 1 4 0m3 0a2 2 0 0 1 4 0M7 13.5q5 1.5 10 0q-5 6.5-10 0");
}

:global(.vnoccubap) {
  d: path("M3 4q9-2.5 18 0v6c0 7-4.5 11.5-9 11.5S3 17 3 10Z");
}

</style>
