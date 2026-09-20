<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lyk3lbb0z"/><path class="ksh4iaclj"/><path class="h0xx2obvc"/><path class="zpl29uvhf"/><path class="voz_x46if"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:elt-outline-bold" {...props}></Icon>
<style>
:global(.h0xx2obvc) {
  d: path("M13 12h3");
}

:global(.ksh4iaclj) {
  d: path("M2 5a5 2.5 0 0 0 10 0");
}

:global(.lyk3lbb0z) {
  d: path("M2 5a5 2.5 0 0 1 10 0v8a5 2.5 0 0 1 -10 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.voz_x46if) {
  d: path("M15 17a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.zpl29uvhf) {
  d: path("m16 9 3 3 -3 3");
}

</style>
