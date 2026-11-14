<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j04urab-q"/><path class="kdsddcc-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pool-robot" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j04urab-q) {
  d: path("M7.75 5.5H13a5.25 5.25 0 0 1 5.25 5.25v.5A5.25 5.25 0 0 1 13 16.5H7.75a5.25 5.25 0 0 1-5.25-5.25v-.5A5.25 5.25 0 0 1 7.75 5.5");
}

:global(.kdsddcc-f) {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6.25-7.5H21m0-3v6M7.5 5.5v-1A1.5 1.5 0 0 1 9 3h3a1.5 1.5 0 0 1 1.5 1.5v1");
}

</style>
