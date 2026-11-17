<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lor2vm6cu"/><path class="y8brb3-1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-1-duocolor-sharp" {...props}></Icon>
<style>
:global(.lor2vm6cu) {
  stroke-opacity: 0.4;
  d: path("M12 10.6V4H5v16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y8brb3-1p) {
  d: path("M3 20h18M9 20v-7l5-4l5 4v7");
}

</style>
