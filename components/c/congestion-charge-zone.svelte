<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jefgrcc3u"/><path class="zla5xc92p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:congestion-charge-zone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jefgrcc3u) {
  d: path("m14.475 4.725l4.8 4.8a3.5 3.5 0 0 1 0 4.95l-4.8 4.8a3.5 3.5 0 0 1-4.95 0l-4.8-4.8a3.5 3.5 0 0 1 0-4.95l4.8-4.8a3.5 3.5 0 0 1 4.95 0");
}

:global(.zla5xc92p) {
  d: path("M14.5 9.5c0-1.25-1.25-1.75-2.5-1.75c-1.5 0-2.5.75-2.5 2c0 2.75 5 1.75 5 4.5c0 1.25-1 2-2.5 2c-1.25 0-2.5-.5-2.5-1.75m2.5-8v11");
}

</style>
