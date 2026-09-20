<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nkm-qac_y"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="zofa9qbxh"/><path class="gn1ganbdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:frozen-checkpoint-duotone-bold" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.gn1ganbdv) {
  d: path("M10.5 10a1.5 1.5 0 0 1 3 0");
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.nkm-qac_y) {
  fill: currentColor;
  d: path("M9 10h6v3H9Z");
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

:global(.zofa9qbxh) {
  d: path("M9 10h6v3H9Z");
}

</style>
