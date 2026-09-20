<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rgm5-92up"/><path class="es-8_jb_y"/><path class="q_xymip_v"/><path class="po47_2bjy"/><path class="oz614acod"/><path class="iqy6wdsji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dance-floor-duotone-regular" {...props}></Icon>
<style>
:global(.es-8_jb_y) {
  fill: currentColor;
  d: path("M13 7h7v6h-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iqy6wdsji) {
  d: path("M8 16h7v5H8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oz614acod) {
  d: path("M13 7h7v6h-7Z");
}

:global(.po47_2bjy) {
  d: path("M3 7h7v6H3Z");
}

:global(.q_xymip_v) {
  fill: currentColor;
  d: path("M8 16h7v5H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rgm5-92up) {
  fill: currentColor;
  d: path("M3 7h7v6H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
