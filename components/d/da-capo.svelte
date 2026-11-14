<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="clg7v8flh"/><path class="xalax7ehx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:da-capo" {...props}></Icon>
<style>
:global(.clg7v8flh) {
  d: path("M14 17v-7a4 4 0 0 0-8 0v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xalax7ehx) {
  d: path("M3.5 13.5L6 16l2.5-2.5m9-9.5v16m3-16v16");
}

</style>
