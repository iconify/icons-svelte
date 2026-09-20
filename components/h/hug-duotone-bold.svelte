<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f96m3ibxz"/><path class="ed0jd0_6k"/><path class="w5km8ibkz"/><path class="txl-1ha9s"/><path class="a9vo92b3c"/><path class="q9l06zbkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hug-duotone-bold" {...props}></Icon>
<style>
:global(.a9vo92b3c) {
  d: path("M2 20v-3a4.5 4.5 0 0 1 9 0v3");
}

:global(.ed0jd0_6k) {
  fill: currentColor;
  d: path("M14.5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.f96m3ibxz) {
  fill: currentColor;
  d: path("M3.5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.q9l06zbkl) {
  d: path("M13 20v-3a4.5 4.5 0 0 1 9 0v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.txl-1ha9s) {
  d: path("M14.5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.w5km8ibkz) {
  d: path("M3.5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
