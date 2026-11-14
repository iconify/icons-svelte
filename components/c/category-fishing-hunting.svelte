<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g01zlll3k"/><path class="ya1x6ob2f"/><path class="fm-d68bwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-fishing-hunting" {...props}></Icon>
<style>
:global(.fm-d68bwr) {
  d: path("M20 3.5V10m0 0v6.5a3.5 3.5 0 0 1-7 0V14m0 0l2 1.75");
}

:global(.g01zlll3k) {
  d: path("M3 21Q7 7 20 3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ya1x6ob2f) {
  fill: currentColor;
  d: path("M2.75 17a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
