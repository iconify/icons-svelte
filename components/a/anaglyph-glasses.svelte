<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iyi5yyb1s"/><path class="dmxgz3b-u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:anaglyph-glasses" {...props}></Icon>
<style>
:global(.dmxgz3b-u) {
  d: path("M13 13a4 4 0 1 0 8 0a4 4 0 1 0-8 0M2.5 9h19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iyi5yyb1s) {
  fill: currentColor;
  d: path("M3 13a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
