<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="parrfubho"/><path class="nr2kwkbiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:group-pay" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nr2kwkbiv) {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

:global(.parrfubho) {
  d: path("M11.763 20.5H3.5c-.6 0-1-.4-1-1c0-3 2.9-5 6.5-5c1.114 0 2.108.198 2.949.595M5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M16 4.5a3.5 3.5 0 0 1 .906 6.881M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
