<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pqqiwbo9y"/><path class="rdml8obcc"/><path class="a6e_o0bju"/><path class="xil7tiu3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-duotone-regular" {...props}></Icon>
<style>
:global(.a6e_o0bju) {
  d: path("m3 11 9 -9 9 9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pqqiwbo9y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 11 9 -9 9 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rdml8obcc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 11v9h12v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xil7tiu3o) {
  d: path("M6 11v9h12v-9");
}

</style>
