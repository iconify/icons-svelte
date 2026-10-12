<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ib6dlem5t"/><path class="jcttu4brj"/><path class="ejx-lm94j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:oven-sharp" {...props}></Icon>
<style>
:global(.ejx-lm94j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 11h10.5v6.75H6.75z");
}

:global(.ib6dlem5t) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 2.75h17.5v18.5H3.25zm0 5h17.5");
}

:global(.jcttu4brj) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5.25h.01m3.49 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
