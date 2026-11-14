<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zbsiwobzn"/><path class="twq03pg1b"/><path class="z9fdbpdjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:convert" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.twq03pg1b) {
  d: path("M17.25 8.75L19.5 11l2.25-2.25M10 19.5H6.5a2 2 0 0 1-2-2V13");
}

:global(.z9fdbpdjf) {
  d: path("M2.25 15.25L4.5 13l2.25 2.25");
}

:global(.zbsiwobzn) {
  d: path("M5.125 2.5h2.25A2.625 2.625 0 0 1 10 5.125v2.25A2.625 2.625 0 0 1 7.375 10h-2.25A2.625 2.625 0 0 1 2.5 7.375v-2.25A2.625 2.625 0 0 1 5.125 2.5M14 17.75a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M14 4.5h3.5a2 2 0 0 1 2 2V11");
}

</style>
