<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p-tzjoy3w"/><path class="na80-rxcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fire-extinguisher-duocolor-round" {...props}></Icon>
<style>
:global(.na80-rxcu) {
  d: path("M9 12a4 4 0 1 1 8 0v5a4 4 0 1 1-8 0zm4-4V5l6-2M9 15h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p-tzjoy3w) {
  stroke-opacity: 0.4;
  d: path("M13 5H9a4 4 0 0 0-4 4v7");
}

</style>
