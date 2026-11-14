<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j48grnb1t"/><path class="jlmhchb-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dwarf-signal" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j48grnb1t) {
  d: path("M5.5 14.5v-5a6.5 6.5 0 0 1 13 0v5Zm6.5 0V21m-4 0h8");
}

:global(.jlmhchb-q) {
  d: path("M10 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
