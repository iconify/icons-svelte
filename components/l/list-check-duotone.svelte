<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ryvt14b8p"/><path class="xi2kx1b1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-check-duotone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ryvt14b8p) {
  stroke-opacity: 0.4;
  d: path("M2 4L22 4M2 11L22 11");
}

:global(.xi2kx1b1h) {
  d: path("M2 18L6 18M10 18L14 18M18 18L20 20L22 16");
}

</style>
