<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t8enobhpe"/><path class="jrp_n8b7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:film-projector" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jrp_n8b7l) {
  d: path("M4.5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m9 5.5l8-3.5m-8 7.5l8 3.5M8 7.5h.01");
}

:global(.t8enobhpe) {
  d: path("M5.125 11h5.75a2.625 2.625 0 0 1 2.625 2.625v2.75A2.625 2.625 0 0 1 10.875 19h-5.75A2.625 2.625 0 0 1 2.5 16.375v-2.75A2.625 2.625 0 0 1 5.125 11");
}

</style>
