<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z_4h_acyz"/><path class="is_4m5cif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-solar-panel-duocolor-sharp" {...props}></Icon>
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

:global(.z_4h_acyz) {
  stroke-opacity: 0.4;
  d: path("M12 18H8l1-8h3m0 0h3l1 8h-4m-3-4h6m-3-4v8");
}

</style>
