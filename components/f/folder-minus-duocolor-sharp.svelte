<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fy_av4utg"/><path class="og2hi81sh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-minus-duocolor-sharp" {...props}></Icon>
<style>
:global(.fy_av4utg) {
  stroke-opacity: 0.4;
  d: path("M9 13h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.og2hi81sh) {
  d: path("M12 6h9v14H3V4h7z");
}

</style>
