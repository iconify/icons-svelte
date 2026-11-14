<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tc3id9jmw"/><path class="ja8_zg6om"/><path class="grn83eohb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:aircraft-rivet" {...props}></Icon>
<style>
:global(.grn83eohb) {
  d: path("M9.292 11.522a2.75 2.75 0 0 1 2.23-2.23");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja8_zg6om) {
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.tc3id9jmw) {
  d: path("M8.625 2.5h6.75A6.125 6.125 0 0 1 21.5 8.625v6.75a6.125 6.125 0 0 1-6.125 6.125h-6.75A6.125 6.125 0 0 1 2.5 15.375v-6.75A6.125 6.125 0 0 1 8.625 2.5");
}

</style>
