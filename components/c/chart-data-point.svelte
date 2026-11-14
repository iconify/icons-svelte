<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ln18mrbuc"/><path class="fun_tx6lq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-data-point" {...props}></Icon>
<style>
:global(.fun_tx6lq) {
  fill: currentColor;
  d: path("M14 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ln18mrbuc) {
  d: path("m2.5 18l5-6.5l4.5 3L16.5 7l5 3.5");
}

</style>
