<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tqyk1xr1x"/><path class="qvcla2bco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-x-two-tone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qvcla2bco) {
  d: path("M2 18H6M10 18H14M18 16L22 20M22 16L18 20");
}

:global(.tqyk1xr1x) {
  stroke-opacity: 0.4;
  d: path("M2 4H22M2 11H22");
}

</style>
