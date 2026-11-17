<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t79xm3bzn"/><path class="bgy7uubjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:glass-water-duocolor-sharp" {...props}></Icon>
<style>
:global(.bgy7uubjz) {
  d: path("M5 3h14l-2 18H7z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t79xm3bzn) {
  stroke-opacity: 0.4;
  d: path("M6 12h12");
}

</style>
