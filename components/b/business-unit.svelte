<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="je520hb2t"/><path class="kq4taj50n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:business-unit" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.je520hb2t) {
  d: path("M10.75 13.25v-8a8 8 0 1 0 8 8Z");
}

:global(.kq4taj50n) {
  d: path("M13.5 10.5v-8a8 8 0 0 1 8 8Z");
}

</style>
