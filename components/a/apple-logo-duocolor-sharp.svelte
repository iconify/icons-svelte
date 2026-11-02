<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fz9xol7fs"/><path class="zwm_h-62j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:apple-logo-duocolor-sharp" {...props}></Icon>
<style>
:global(.fz9xol7fs) {
  stroke-opacity: 0.4;
  d: path("M12 9c-1 0-2.5-1-4-1c-2.5 0-4 2.5-4 5c0 4 2 8 4 8c1.5 0 2.5-1 4-1s2.5 1 4 1s3-2 4-4c-2-1-3-2-3-4c0-1.5 1-2.5 2-3c-1-1.5-2-2-3-2c-1.5 0-3 1-4 1");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zwm_h-62j) {
  d: path("M12 5a2 2 0 0 1 2-2a2 2 0 0 1-2 2");
}

</style>
