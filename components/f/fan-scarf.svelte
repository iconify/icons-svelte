<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wgemdacqj"/><path class="sf2n1n1um"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fan-scarf" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sf2n1n1um) {
  d: path("M10 10.75L8.5 19.5H13l1-8.75m-4.75 4.5h4.25m-4 4.25v2m2.75-2v2");
}

:global(.wgemdacqj) {
  d: path("M5 2.5v3C5 9.25 8 11 12 11s7-1.75 7-5.5v-3");
}

</style>
