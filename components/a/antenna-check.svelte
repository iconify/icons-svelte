<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g2c0pdi9p"/><path class="ehz4xh3jc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:antenna-check" {...props}></Icon>
<style>
:global(.ehz4xh3jc) {
  d: path("M7.5 21.5L10 9l2.5 12.5m-7-18a6 6 0 0 0 0 8m9-8a6 6 0 0 1 0 8m.25 6.5l2 2L21 15.75");
}

:global(.g2c0pdi9p) {
  d: path("M8.5 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
