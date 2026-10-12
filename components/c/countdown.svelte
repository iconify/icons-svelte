<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fznlw_bwv"/><path class="nli-rgbxh"/><path class="ah4jhb0mz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:countdown" {...props}></Icon>
<style>
:global(.ah4jhb0mz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 12l3.25-2.25M12 12v3.75");
}

:global(.fznlw_bwv) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12V2.75A9.25 9.25 0 1 1 2.75 12Z");
}

:global(.nli-rgbxh) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.31 8.84h.01m2.14-3.38h.01m3.37-2.15h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
