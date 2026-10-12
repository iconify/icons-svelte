<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kkjj_7fin"/><path class="edrh-mb1w"/><circle class="ba76p1n5h"/><path class="a0rzm1pyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:moon-base-sharp" {...props}></Icon>
<style>
:global(.a0rzm1pyk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 6h.01M10 3.75h.01");
}

:global(.ba76p1n5h) {
  cx: 17.75px;
  cy: 6.25px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.edrh-mb1w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 16.5h11.5m-7.25 4v-3.75h3v3.75m-10.25 0H4.5m14 0h2.75");
}

:global(.kkjj_7fin) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20.5a7 7 0 0 1 14 0Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
