<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4rnrvbzy"/><path class="bcrqezb5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:camera-duocolor-sharp" {...props}></Icon>
<style>
:global(.bcrqezb5d) {
  d: path("M3 7h4l3-3h4l3 3h4v13H3z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y4rnrvbzy) {
  stroke-opacity: 0.4;
  d: path("M9 13a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
