<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="walbv2b5n"/><path class="rg6qytb9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heading-3-two-tone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rg6qytb9d) {
  d: path("M17 13H21L18.8564 16C20.0403 16 21 16.8954 21 18C21 19.1046 20.0403 20 18.8564 20C18.0906 20 17.3829 19.6188 17 19");
}

:global(.walbv2b5n) {
  stroke-opacity: 0.4;
  d: path("M2 4V20M11 4V20M2 12H11");
}

</style>
