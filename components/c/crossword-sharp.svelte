<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zt0uddb5s"/><path class="erg1mi22d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crossword-sharp" {...props}></Icon>
<style>
:global(.erg1mi22d) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 4h4v4h-4Zm1 2h2M4 16h4v4H4Zm1 2h2");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.zt0uddb5s) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h18v18H3zm6 0v18m6-18v18M3 9h18M3 15h18");
}

</style>
