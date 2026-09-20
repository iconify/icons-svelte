<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m3tfe9bwc"/><path class="mjze8rg7o"/><path class="qj5yzibzr"/><path class="g_okxob7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:filtered-list-duotone-bold" {...props}></Icon>
<style>
:global(.g_okxob7c) {
  d: path("M9 19.5h6");
}

:global(.m3tfe9bwc) {
  fill: currentColor;
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mjze8rg7o) {
  d: path("M9 2.5H3l7 7V12h4V9.5l7 -7h-6");
}

:global(.qj5yzibzr) {
  d: path("M9 16.5h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
