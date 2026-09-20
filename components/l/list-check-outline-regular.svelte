<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="a4w3m-uwg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-check-outline-regular" {...props}></Icon>
<style>
:global(.a4w3m-uwg) {
  d: path("m16 12 2.5 2.5L22 11");
}

:global(.ldkstzszf) {
  d: path("M3 16h11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nrqy16b7j) {
  d: path("M3 6h11");
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

</style>
