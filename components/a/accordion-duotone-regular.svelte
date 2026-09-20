<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cc4aslbnx"/><path class="p6x0gmb9n"/><path class="ox5l_oflw"/><path class="v7gkhsjxx"/><path class="lyv456b1p"/><path class="ulz6wxb8x"/><path class="tkg_kabnx"/><path class="i0n60fn-c"/><path class="x22av82oi"/><path class="rhuo4pbym"/><path class="hd4xf-4qm"/><path class="bgh_rqbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:accordion-duotone-regular" {...props}></Icon>
<style>
:global(.bgh_rqbkv) {
  d: path("m17 17.5 2 2 2 -2");
}

:global(.cc4aslbnx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hd4xf-4qm) {
  d: path("M3 19h11");
}

:global(.i0n60fn-c) {
  d: path("m17 3.5 2 2 2 -2");
}

:global(.lyv456b1p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ox5l_oflw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p6x0gmb9n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 3.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rhuo4pbym) {
  d: path("m17 13.5 2 -2 2 2");
}

:global(.tkg_kabnx) {
  d: path("M3 5h11");
}

:global(.ulz6wxb8x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 17.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v7gkhsjxx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 13.5 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x22av82oi) {
  d: path("M3 12h11");
}

</style>
