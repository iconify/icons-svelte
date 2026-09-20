<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mpszpfbjn"/><path class="fmulrlbrn"/><path class="fmma7fifq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:layer-duotone-bold" {...props}></Icon>
<style>
:global(.fmma7fifq) {
  d: path("M8 22h8");
}

:global(.fmulrlbrn) {
  d: path("m4 12 8 -8 8 8 -8 8Z");
}

:global(.mpszpfbjn) {
  fill: currentColor;
  d: path("m4 12 8 -8 8 8 -8 8Z");
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

</style>
