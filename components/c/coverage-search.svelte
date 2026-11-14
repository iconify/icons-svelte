<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bhol-ebqy"/><path class="hafdiebya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coverage-search" {...props}></Icon>
<style>
:global(.bhol-ebqy) {
  d: path("M10 11v10m-2.5 0h5M6.25 9.75a4 4 0 0 1 7.5 0");
}

:global(.hafdiebya) {
  d: path("M2.5 8.25a8 8 0 0 1 15 0m-2.25 9.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
