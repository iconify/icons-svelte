<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eodvx3bcu"/><path class="fky8vgb_s"/><path class="d-ycm7dex"/><path class="tw1khnbtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:quantize-4bit-duotone-bold" {...props}></Icon>
<style>
:global(.d-ycm7dex) {
  d: path("m3 9 6 -6");
}

:global(.eodvx3bcu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 9 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fky8vgb_s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h5v-5h5v-5h5V6h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tw1khnbtv) {
  d: path("M3 21h5v-5h5v-5h5V6h3");
}

</style>
