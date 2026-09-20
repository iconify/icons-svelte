<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oibtokbpn"/><path class="a1e57xbge"/><path class="an1d4_bjs"/><path class="mbtdyzb2z"/><path class="uih_zvhtv"/><path class="sg0msuxxt"/><path class="b6bpk4b8h"/><path class="fevuzkbbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:microscope-duotone-thin" {...props}></Icon>
<style>
:global(.a1e57xbge) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.an1d4_bjs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 21v-4h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b6bpk4b8h) {
  d: path("M11 17v-6l5 -5");
}

:global(.fevuzkbbx) {
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mbtdyzb2z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 17v-6l5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oibtokbpn) {
  fill: currentColor;
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sg0msuxxt) {
  d: path("M7 21v-4h8");
}

:global(.uih_zvhtv) {
  d: path("M4 21h16");
}

</style>
