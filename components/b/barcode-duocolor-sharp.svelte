<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x7irwtb8m"/><path class="ld1vm1efx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:barcode-duocolor-sharp" {...props}></Icon>
<style>
:global(.ld1vm1efx) {
  d: path("M4 5v14m8-14v14m8-14v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x7irwtb8m) {
  stroke-opacity: 0.4;
  d: path("M8 5v14m8-14v14");
}

</style>
