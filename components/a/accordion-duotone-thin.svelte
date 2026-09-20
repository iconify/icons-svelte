<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oa7csmxww"/><path class="bkr2y1zsz"/><path class="cv60iqboi"/><path class="v-niq62yu"/><path class="h2pllt69t"/><path class="z8-9pyb5d"/><path class="tkg_kabnx"/><path class="i0n60fn-c"/><path class="x22av82oi"/><path class="rhuo4pbym"/><path class="hd4xf-4qm"/><path class="bgh_rqbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:accordion-duotone-thin" {...props}></Icon>
<style>
:global(.bgh_rqbkv) {
  d: path("m17 17.5 2 2 2 -2");
}

:global(.bkr2y1zsz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 3.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cv60iqboi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h2pllt69t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hd4xf-4qm) {
  d: path("M3 19h11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i0n60fn-c) {
  d: path("m17 3.5 2 2 2 -2");
}

:global(.oa7csmxww) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rhuo4pbym) {
  d: path("m17 13.5 2 -2 2 2");
}

:global(.tkg_kabnx) {
  d: path("M3 5h11");
}

:global(.v-niq62yu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 13.5 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x22av82oi) {
  d: path("M3 12h11");
}

:global(.z8-9pyb5d) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 17.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
