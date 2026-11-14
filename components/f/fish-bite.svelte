<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q5x4llbge"/><path class="y02u40its"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fish-bite" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q5x4llbge) {
  d: path("M7.5 11a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m6.039-4.229l1.026-2.819");
}

:global(.y02u40its) {
  d: path("M2.5 15q2.5-1.75 5 0H10m4 0h2.5q2.5 1.75 5 0M7.771 9.461l8.458 3.078M6.5 18.75q5.5 3 11 0");
}

</style>
