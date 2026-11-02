<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t0kd1md4b"/><path class="t2hdo3h8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microscope-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t0kd1md4b) {
  stroke-opacity: 0.4;
  d: path("M14 21a6 6 0 0 0 6-6a5 5 0 0 0-5-5h-2");
}

:global(.t2hdo3h8p) {
  d: path("M7 6h6v7H7zm1 0V3h4v3M3 21h18M6 17h8");
}

</style>
