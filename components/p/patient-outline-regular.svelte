<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzln5b9mk"/><path class="m549s9bpo"/><path class="pmuiqo95v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:patient-outline-regular" {...props}></Icon>
<style>
:global(.jzln5b9mk) {
  d: path("M4 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.m549s9bpo) {
  d: path("M2 20v-6h20v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

</style>
