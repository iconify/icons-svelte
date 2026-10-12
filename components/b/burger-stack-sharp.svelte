<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="agcy0y53w"/><path class="nkwhnfxcf"/><path class="vih6mbbbp"/><path class="tdj0jgbft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:burger-stack-sharp" {...props}></Icon>
<style>
:global(.agcy0y53w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6.5a7.5 3.75 0 0 1 15 0v.75h-15z");
}

:global(.nkwhnfxcf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 5h.01m4.99 0h.01");
}

:global(.tdj0jgbft) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13h8.25l1.25 1.75L14 13h6.75M4 18.75h16v2.5H4z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vih6mbbbp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.5h17.5v7H3.25z");
}

</style>
