<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ebvczzbhc"/><path class="vwibguupl"/><path class="qjhi8_b0z"/><path class="sxlwlmkmh"/><path class="hzsvawc8s"/><path class="u8aszkb6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-left-right-duotone-bold" {...props}></Icon>
<style>
:global(.ebvczzbhc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hzsvawc8s) {
  d: path("m8 8 -4 4 4 4");
}

:global(.qjhi8_b0z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 8 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.u8aszkb6i) {
  d: path("m16 8 4 4 -4 4");
}

:global(.vwibguupl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
