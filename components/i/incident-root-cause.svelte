<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vtq4febbd"/><path class="knlz_6bba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:incident-root-cause" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.knlz_6bba) {
  d: path("M3 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m17-4V18m0 3h.01");
}

:global(.vtq4febbd) {
  d: path("M10 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 3v3m-7 4v-4h14");
}

</style>
