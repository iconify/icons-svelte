<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="doy9q4b5f"/><path class="fjf7bob9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-transfer-diagonal-line-duotone" {...props}></Icon>
<style>
:global(.doy9q4b5f) {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.fjf7bob9l) {
  stroke-linejoin: round;
  d: path("M6.2998 3.7832L13.8786 12.0005L13.8785 7.50064M17.7006 20.2178L9.87852 12.001L9.87853 16.5005");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
