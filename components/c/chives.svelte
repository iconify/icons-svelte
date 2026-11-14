<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ept0mpmgh"/><path class="iq_9wjbit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chives" {...props}></Icon>
<style>
:global(.ept0mpmgh) {
  d: path("M5 3.5L9 16v5.5m3-19v19M17 8l-2 8v5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iq_9wjbit) {
  d: path("M15.25 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M7.5 16h9");
}

</style>
