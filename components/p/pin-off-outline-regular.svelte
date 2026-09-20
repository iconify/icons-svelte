<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c7kjqqh8k"/><path class="dsyn-2b9s"/><path class="nnj9-vbsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pin-off-outline-regular" {...props}></Icon>
<style>
:global(.c7kjqqh8k) {
  d: path("M7 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.dsyn-2b9s) {
  d: path("M10 10v7");
}

:global(.nnj9-vbsr) {
  d: path("M5 21 19 7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
