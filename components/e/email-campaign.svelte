<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zgqgox79d"/><path class="uyjz5fiwx"/><path class="n24bspbit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:email-campaign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n24bspbit) {
  d: path("m2.5 10l7.5 4.5l7.5-4.5");
}

:global(.uyjz5fiwx) {
  d: path("M6 8h8a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 14 19H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 8");
}

:global(.zgqgox79d) {
  d: path("M6.5 8V6a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-2");
}

</style>
