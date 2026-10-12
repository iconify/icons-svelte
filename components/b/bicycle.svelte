<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4z8cvisi"/><circle class="drobnoznw"/><circle class="em4k7_b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bicycle" {...props}></Icon>
<style>
:global(.drobnoznw) {
  cx: 5.5px;
  cy: 17px;
  r: 2.75px;
}

:global(.em4k7_b5o) {
  cx: 18.5px;
  cy: 17px;
  r: 2.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u4z8cvisi) {
  d: path("M8.25 17H11L9.6 9.25m-1.35 0H11m-.95 2.5h6.59M11 17l5.2-6.5m-.7-2l2.08 5.91M15.5 8.5h2A1.5 1.5 0 0 1 19 10v.75");
}

</style>
