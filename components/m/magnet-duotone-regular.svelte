<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zaintx98k"/><path class="thkmlu7qy"/><path class="coye-i88w"/><path class="i-58-pnpd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:magnet-duotone-regular" {...props}></Icon>
<style>
:global(.coye-i88w) {
  d: path("M8 8v8");
}

:global(.i-58-pnpd) {
  d: path("M16 8v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.thkmlu7qy) {
  d: path("M3 8h18v8H3Z");
}

:global(.zaintx98k) {
  fill: currentColor;
  d: path("M3 8h18v8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
