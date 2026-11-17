<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jps9vkgsi"/><path class="ingoogvsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fuse-duocolor-sharp" {...props}></Icon>
<style>
:global(.ingoogvsx) {
  d: path("M5 3h14v3h-2v12h2v3H5v-3h2V6H5z");
}

:global(.jps9vkgsi) {
  stroke-opacity: 0.4;
  d: path("m13 8l-3 4h4l-3 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
