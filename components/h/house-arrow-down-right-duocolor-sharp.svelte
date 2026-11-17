<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jgjwo7bbf"/><path class="is_4m5cif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-arrow-down-right-duocolor-sharp" {...props}></Icon>
<style>
:global(.is_4m5cif) {
  d: path("m12 3l8 7v11H4V10z");
}

:global(.jgjwo7bbf) {
  stroke-opacity: 0.4;
  d: path("M11 17h4v-4m0 4l-6-6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
