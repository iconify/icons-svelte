<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fed2k6bxs"/><path class="mkzojhn9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gravel-trap" {...props}></Icon>
<style>
:global(.fed2k6bxs) {
  d: path("M2.5 9c5.5 0 7-3 7-6.5M2.5 14c8 0 12-5 12-11.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mkzojhn9z) {
  fill: currentColor;
  d: path("M21.5 5v16.5H5c7 0 16.5-8.5 16.5-16.5");
}

</style>
