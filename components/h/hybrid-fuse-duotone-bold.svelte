<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hpqcztb8d"/><path class="xog9qqp-s"/><path class="map-hhy3d"/><path class="had9dk06e"/><path class="pr6npvbsh"/><path class="xxvssxb6x"/><path class="lqiw_3bos"/><path class="dhtq24lfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hybrid-fuse-duotone-bold" {...props}></Icon>
<style>
:global(.dhtq24lfs) {
  d: path("m17 9.5 2.5 2.5 -2.5 2.5");
}

:global(.had9dk06e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 9.5 2.5 2.5 -2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hpqcztb8d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 5 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lqiw_3bos) {
  d: path("M10 12h7");
}

:global(.map-hhy3d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pr6npvbsh) {
  d: path("m3 5 6 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xog9qqp-s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 19 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xxvssxb6x) {
  d: path("m3 19 6 -6");
}

</style>
