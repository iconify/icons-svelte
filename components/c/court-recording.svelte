<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z8-6qn24o"/><path class="s1g6tytlb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:court-recording" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s1g6tytlb) {
  d: path("M3.5 10a6 6 0 0 0 12 0m-6 6v4.5m-3 0h6m3-2a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.z8-6qn24o) {
  d: path("M9.5 2.5zA3.5 3.5 0 0 1 13 6v3a3.5 3.5 0 0 1-3.5 3.5A3.5 3.5 0 0 1 6 9V6a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
