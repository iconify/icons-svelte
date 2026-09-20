<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="s0sz1tb6l"/><path class="dwxywcb3g"/><path class="n45vxib8e"/><path class="arnw7mcql"/><path class="dpohn7bnp"/><path class="lnadppbtp"/><path class="tkg_kabnx"/><path class="i0n60fn-c"/><path class="x22av82oi"/><path class="rhuo4pbym"/><path class="hd4xf-4qm"/><path class="bgh_rqbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:accordion-duotone-bold" {...props}></Icon>
<style>
:global(.arnw7mcql) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 13.5 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bgh_rqbkv) {
  d: path("m17 17.5 2 2 2 -2");
}

:global(.dpohn7bnp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dwxywcb3g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 3.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hd4xf-4qm) {
  d: path("M3 19h11");
}

:global(.i0n60fn-c) {
  d: path("m17 3.5 2 2 2 -2");
}

:global(.lnadppbtp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 17.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n45vxib8e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rhuo4pbym) {
  d: path("m17 13.5 2 -2 2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s0sz1tb6l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tkg_kabnx) {
  d: path("M3 5h11");
}

:global(.x22av82oi) {
  d: path("M3 12h11");
}

</style>
