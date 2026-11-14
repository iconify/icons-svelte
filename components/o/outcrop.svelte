<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h7ray43gz"/><path class="julv8sb5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:outcrop" {...props}></Icon>
<style>
:global(.h7ray43gz) {
  d: path("M3.5 20L6 12.5l4-3l3-5l4.5 3L20 20M2.5 20h19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.julv8sb5z) {
  d: path("m5 15.5l6-3h7.5");
}

</style>
