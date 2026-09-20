<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jy3h3p6ze"/><path class="bqf2peb4s"/><path class="uhkbmlahb"/><path class="vmh-l_baq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-up-right-duotone-bold" {...props}></Icon>
<style>
:global(.bqf2peb4s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 5 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jy3h3p6ze) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20V10h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uhkbmlahb) {
  d: path("M4 20V10h16");
}

:global(.vmh-l_baq) {
  d: path("m15 5 5 5 -5 5");
}

</style>
