<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ph8gnzbfo"/><path class="dh9t8vo3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrow-curve-down-right" {...props}></Icon>
<style>
:global(.dh9t8vo3f) {
  d: path("M11 21h5v-5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ph8gnzbfo) {
  d: path("M8 3v7c0 2 .75 3.75 2 5l6 6");
}

</style>
