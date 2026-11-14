<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xmumt86wb"/><path class="pxfsbcccr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:key-tag" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pxfsbcccr) {
  d: path("M6.25 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M15 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.xmumt86wb) {
  d: path("M4.5 3h7l9.5 9.5l-1 1h-5.75a2 2 0 0 0-2 2v5l-.75.5L3 11.5v-7A1.5 1.5 0 0 1 4.5 3");
}

</style>
