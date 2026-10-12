<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="t6xlinugs"/><path class="w8ehhfbko"/><path class="exjtf0cfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:face-shield-med-sharp" {...props}></Icon>
<style>
:global(.exjtf0cfp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 16h3m3-5.5v5.75l-1.25 1.25");
}

:global(.t6xlinugs) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.75h16v3H4zm1 5.5h14v6c0 4-3 7-7 7s-7-3-7-7Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.w8ehhfbko) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 11.75h.01m4.99 0h.01");
}

</style>
