<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qt13nffyn"/><path class="l0v-b4kbr"/><path class="oyo-f5llb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:egress-fee-outline-regular" {...props}></Icon>
<style>
:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oyo-f5llb) {
  d: path("M16 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.qt13nffyn) {
  d: path("M3 6a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
