<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6ca27bzw"/><path class="l4idv55xn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beeper-pager" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l4idv55xn) {
  d: path("M7.75 10h8.5A1.75 1.75 0 0 1 18 11.75v2.5A1.75 1.75 0 0 1 16.25 16h-8.5A1.75 1.75 0 0 1 6 14.25v-2.5A1.75 1.75 0 0 1 7.75 10m.75 3H13");
}

:global(.p6ca27bzw) {
  d: path("M7.375 7h9.25A4.375 4.375 0 0 1 21 11.375v4.25A4.375 4.375 0 0 1 16.625 20h-9.25A4.375 4.375 0 0 1 3 15.625v-4.25A4.375 4.375 0 0 1 7.375 7M17.5 3.5V7");
}

</style>
