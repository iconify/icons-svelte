<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bypaybsio"/><path class="aaf68ub-v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:goal-tile-09" {...props}></Icon>
<style>
:global(.aaf68ub-v) {
  d: path("M6.5 13a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m4.5 0h.01M11 13L21.5 2.5M19 2.25V5h2.75");
}

:global(.bypaybsio) {
  d: path("M2.5 13a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
