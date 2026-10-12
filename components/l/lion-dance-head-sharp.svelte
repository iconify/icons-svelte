<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pbvadyxbr"/><path class="cykxfgb2d"/><path class="hgq5u2bur"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lion-dance-head-sharp" {...props}></Icon>
<style>
:global(.cykxfgb2d) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 10.25h.01m5.49 0h.01");
}

:global(.hgq5u2bur) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 14.25h8a4 3.25 0 0 1-8 0ZM3.75 9a1 1 0 0 0 0 2a1 1 0 0 0 0 2a1 1 0 0 0 0 2a1 1 0 0 0 0 2m16.5-8a1 1 0 0 1 0 2a1 1 0 0 1 0 2a1 1 0 0 1 0 2a1 1 0 0 1 0 2");
}

:global(.pbvadyxbr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6V2.75M6 6h12v15.25H6z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
