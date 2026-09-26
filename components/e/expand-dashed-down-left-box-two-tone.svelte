<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wu6-uy96e"/><path class="af7l3rbrg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-left-box-two-tone" {...props}></Icon>
<style>
:global(.af7l3rbrg) {
  stroke-opacity: 0.4;
  d: path("M8 21L6 21M3 18L3 16M6 13L8 13M11 18L11 16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wu6-uy96e) {
  d: path("M18 11L18 21M15 18L18 21L21 18M13 6L3 6M6 3L3 6L6 9");
}

</style>
