<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bxvp6ib-c"/><path class="yc_5gkigy"/><path class="dp8rry9sk"/><path class="zid7cdc0n"/><path class="w395fxb3e"/><path class="tcxfk34nj"/><path class="xsyfe-byx"/><path class="ehef6tbzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:paint-palette-duotone-bold" {...props}></Icon>
<style>
:global(.bxvp6ib-c) {
  fill: currentColor;
  d: path("M12 3a9 9 0 1 0 0 18 2.5 2.5 0 0 0 0 -5 2 2 0 0 1 0 -4h5a4 4 0 0 0 4 -4c0 -3 -4 -5 -9 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.dp8rry9sk) {
  fill: currentColor;
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ehef6tbzw) {
  d: path("M10 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tcxfk34nj) {
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.w395fxb3e) {
  d: path("M12 3a9 9 0 1 0 0 18 2.5 2.5 0 0 0 0 -5 2 2 0 0 1 0 -4h5a4 4 0 0 0 4 -4c0 -3 -4 -5 -9 -5");
}

:global(.xsyfe-byx) {
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.yc_5gkigy) {
  fill: currentColor;
  d: path("M7 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zid7cdc0n) {
  fill: currentColor;
  d: path("M10 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
