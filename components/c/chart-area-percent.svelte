<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lg-8n1num"/><path class="my21nhd9n"/><path class="p_4ejy8rr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-area-percent" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lg-8n1num) {
  d: path("M5 3h14a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2");
}

:global(.my21nhd9n) {
  d: path("M3 9.5c3.5-3 6.5 2 10-1c3-2.5 5.5-1.5 8-2");
}

:global(.p_4ejy8rr) {
  fill: currentColor;
  d: path("M3 15c3.5-2.5 6.5 2 10-1c3-2.5 5.5-1.5 8-2v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
