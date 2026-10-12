<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ox05rfewb"/><circle class="wcwdkbbur"/><path class="h3qkj9bop"/><path class="fpk68_bsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dj-deck-sharp" {...props}></Icon>
<style>
:global(.fpk68_bsl) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 7.5v6l-2.25 2.25");
}

:global(.h3qkj9bop) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12h.01");
}

:global(.ox05rfewb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wcwdkbbur) {
  cx: 10px;
  cy: 12px;
  r: 4.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
