<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vxa2dmz6j"/><path class="z-u-ue7vh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-close-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vxa2dmz6j) {
  stroke-opacity: 0.4;
  d: path("m16 16l4 4m0-4l-4 4");
}

:global(.z-u-ue7vh) {
  d: path("M19 11a8 8 0 1 0-8 8m0-12v4h3");
}

</style>
