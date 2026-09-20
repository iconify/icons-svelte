<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xa771-t-o"/><path class="g164o9b0d"/><path class="ugdbidcqi"/><path class="elc06ob4j"/><path class="ayfcapvsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-cost-cap-duotone-thin" {...props}></Icon>
<style>
:global(.ayfcapvsy) {
  d: path("M9 13a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.elc06ob4j) {
  d: path("M8 8h8");
}

:global(.g164o9b0d) {
  fill: currentColor;
  d: path("M9 13a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ugdbidcqi) {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

:global(.xa771-t-o) {
  fill: currentColor;
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
