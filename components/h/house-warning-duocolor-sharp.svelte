<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i8lrfn7rs"/><path class="is_4m5cif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-warning-duocolor-sharp" {...props}></Icon>
<style>
:global(.i8lrfn7rs) {
  stroke-opacity: 0.4;
  d: path("M12 11v3m0 3h.01");
}

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

</style>
