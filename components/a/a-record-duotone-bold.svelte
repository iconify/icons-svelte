<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ph7m0rcoy"/><path class="xgrfb-bqu"/><path class="sprybdcan"/><path class="xsa445osm"/><path class="w7sxxlcqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:a-record-duotone-bold" {...props}></Icon>
<style>
:global(.ph7m0rcoy) {
  fill: currentColor;
  d: path("M3 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sprybdcan) {
  d: path("M3 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.w7sxxlcqv) {
  d: path("m18 12 3 3 -3 3");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.xsa445osm) {
  d: path("M9 15h7");
}

</style>
