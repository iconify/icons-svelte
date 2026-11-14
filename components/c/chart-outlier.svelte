<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8u760b4u"/><path class="rtcdcdcjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-outlier" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p8u760b4u) {
  d: path("M3.5 3v17.5H21");
}

:global(.rtcdcdcjq) {
  d: path("m6.5 17l3-3.5l3.5 2l3.5-3.5l3.5 2M9 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 0h.01");
}

</style>
