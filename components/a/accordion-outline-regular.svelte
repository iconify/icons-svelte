<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tkg_kabnx"/><path class="i0n60fn-c"/><path class="x22av82oi"/><path class="rhuo4pbym"/><path class="hd4xf-4qm"/><path class="bgh_rqbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:accordion-outline-regular" {...props}></Icon>
<style>
:global(.bgh_rqbkv) {
  d: path("m17 17.5 2 2 2 -2");
}

:global(.hd4xf-4qm) {
  d: path("M3 19h11");
}

:global(.i0n60fn-c) {
  d: path("m17 3.5 2 2 2 -2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rhuo4pbym) {
  d: path("m17 13.5 2 -2 2 2");
}

:global(.tkg_kabnx) {
  d: path("M3 5h11");
}

:global(.x22av82oi) {
  d: path("M3 12h11");
}

</style>
