<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="walbv2b5n"/><path class="fx3ouxv1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-4-two-tone" {...props}></Icon>
<style>
:global(.fx3ouxv1x) {
  d: path("M17 13V17.5H22M21 13V20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.walbv2b5n) {
  stroke-opacity: 0.4;
  d: path("M2 4V20M11 4V20M2 12H11");
}

</style>
