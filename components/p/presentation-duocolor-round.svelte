<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vorzg9apl"/><path class="cyztrybfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:presentation-duocolor-round" {...props}></Icon>
<style>
:global(.cyztrybfm) {
  d: path("M5 3v9a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V3M3 3h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vorzg9apl) {
  stroke-opacity: 0.4;
  d: path("m12 16l-5 5m5-5l5 5");
}

</style>
