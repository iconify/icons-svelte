<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rg7qsoywn"/><path class="x2ho6y6-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arm-track" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rg7qsoywn) {
  d: path("M10.875 3h2.25A7.875 7.875 0 0 1 21 10.875v2.25A7.875 7.875 0 0 1 13.125 21h-2.25A7.875 7.875 0 0 1 3 13.125v-2.25A7.875 7.875 0 0 1 10.875 3");
}

:global(.x2ho6y6-n) {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
