<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dktry7bqc"/><path class="k3pzaihav"/><path class="mcfskybik"/><path class="fhl-jdbuu"/><path class="lmyalibdp"/><path class="bo51iypxr"/><path class="tp8vjxbvr"/><path class="cvdxfrhpf"/><path class="razwus2gf"/><path class="b_28-wbex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hurricane-duotone-bold" {...props}></Icon>
<style>
:global(.b_28-wbex) {
  d: path("M6 12v8h7");
}

:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.cvdxfrhpf) {
  d: path("M18 12a6 6 0 0 1 -12 0");
}

:global(.dktry7bqc) {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fhl-jdbuu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 12V4h-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k3pzaihav) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmyalibdp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 12v8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mcfskybik) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 12a6 6 0 0 1 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.razwus2gf) {
  d: path("M18 12V4h-7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tp8vjxbvr) {
  d: path("M6 12a6 6 0 0 1 12 0");
}

</style>
