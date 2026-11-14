<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o6haz77bt"/><path class="g28ek4iud"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:grooming-table" {...props}></Icon>
<style>
:global(.g28ek4iud) {
  d: path("M11 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o6haz77bt) {
  d: path("M3 13h18m-9 0v7.5m-4 0h8m3-7.5V4h-6v2");
}

</style>
