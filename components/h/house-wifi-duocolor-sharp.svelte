<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w0r3c-zdf"/><path class="is_4m5cif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-wifi-duocolor-sharp" {...props}></Icon>
<style>
:global(.is_4m5cif) {
  d: path("m12 3l8 7v11H4V10z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w0r3c-zdf) {
  stroke-opacity: 0.4;
  d: path("M10 15a2.83 2.83 0 0 1 4 0m-7-2c2.563-3.204 7.437-3.204 10 0m-5 5h.01");
}

</style>
