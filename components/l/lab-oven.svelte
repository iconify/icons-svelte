<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfrmd1bms"/><path class="l1mb25ssr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lab-oven" {...props}></Icon>
<style>
:global(.gfrmd1bms) {
  d: path("M6.5 3h11A3.5 3.5 0 0 1 21 6.5v11a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5v-11A3.5 3.5 0 0 1 6.5 3M3 9h18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l1mb25ssr) {
  d: path("M8.75 12h6.5A1.75 1.75 0 0 1 17 13.75v2.5A1.75 1.75 0 0 1 15.25 18h-6.5A1.75 1.75 0 0 1 7 16.25v-2.5A1.75 1.75 0 0 1 8.75 12M7 6h.01M11 6h.01");
}

</style>
