<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j8_f7nbih"/><path class="vvb9ps5lf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:contract-start" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8_f7nbih) {
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v7.75A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-7.75A4.375 4.375 0 0 1 7.375 4.5M8 2.5v4m8-4v4");
}

:global(.vvb9ps5lf) {
  d: path("m11.75 10.298l1.998 1.153a1.5 1.5 0 0 1 0 2.598l-1.998 1.153a1.5 1.5 0 0 1-2.25-1.299v-2.306a1.5 1.5 0 0 1 2.25-1.299");
}

</style>
