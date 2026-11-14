<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wbsiky0ms"/><path class="pjillmbpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gold-panning" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pjillmbpp) {
  d: path("m11.108 8.183l1.098-.313A1.49 1.49 0 0 1 14 8.75a1.106 1.106 0 0 1-.823 1.498l-1.544.29a1.19 1.19 0 0 1-1.383-.913a1.223 1.223 0 0 1 .858-1.442");
}

:global(.wbsiky0ms) {
  d: path("m2.5 4.5l4 8l11 2l4-6.5M3 19q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
