<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="klfam5bdb"/><path class="w9ho0yb9i"/><path class="jyamh529i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:contrast-check" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jyamh529i) {
  d: path("M14.5 16.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

:global(.klfam5bdb) {
  fill: currentColor;
  d: path("M6.5 3h3A3.5 3.5 0 0 1 13 6.5v3A3.5 3.5 0 0 1 9.5 13h-3A3.5 3.5 0 0 1 3 9.5v-3A3.5 3.5 0 0 1 6.5 3");
}

:global(.w9ho0yb9i) {
  d: path("M13.375 9h3.25A4.375 4.375 0 0 1 21 13.375v3.25A4.375 4.375 0 0 1 16.625 21h-3.25A4.375 4.375 0 0 1 9 16.625v-3.25A4.375 4.375 0 0 1 13.375 9");
}

</style>
