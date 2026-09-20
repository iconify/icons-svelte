<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m3tfe9bwc"/><path class="mjze8rg7o"/><path class="olzrbkb7x"/><path class="mo-ktlbjm"/><path class="te5l3v53b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fusion-rank-duotone-bold" {...props}></Icon>
<style>
:global(.m3tfe9bwc) {
  fill: currentColor;
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mjze8rg7o) {
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
}

:global(.mo-ktlbjm) {
  d: path("M10.5 18h3");
}

:global(.olzrbkb7x) {
  d: path("M9 15.5v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.te5l3v53b) {
  d: path("M15 15.5v5");
}

</style>
