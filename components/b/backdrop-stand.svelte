<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_frlqb1j"/><path class="n-hhsg8tm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:backdrop-stand" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n_frlqb1j) {
  d: path("M2.5 21h3M4 21V4h16v17m-1.5 0h3");
}

:global(.n-hhsg8tm) {
  d: path("M7 4v12h10V4");
}

</style>
