<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z28a-lbzn"/><path class="he_knpd7u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:anatomy" {...props}></Icon>
<style>
:global(.he_knpd7u) {
  d: path("m12 18.5l-3.25-3.25A2 2 0 0 1 12 12.5a2 2 0 0 1 3.25 2.75Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z28a-lbzn) {
  d: path("M10 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M5.25 21.5V12a3 3 0 0 1 3-3h7.5a3 3 0 0 1 3 3v9.5");
}

</style>
