<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aivahsbib"/><path class="ima6n9biw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:freshness-check" {...props}></Icon>
<style>
:global(.aivahsbib) {
  d: path("M4 20C4 11 9.5 4 20 4c0 10.5-7 16-16 16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ima6n9biw) {
  d: path("M8.5 12.5L11 15l4.5-5.5");
}

</style>
