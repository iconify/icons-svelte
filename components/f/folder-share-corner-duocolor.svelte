<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t94iyvbtl"/><path class="glkq_3w0k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-share-corner-duocolor" {...props}></Icon>
<style>
:global(.glkq_3w0k) {
  d: path("M12 6h7a2 2 0 0 1 2 2M8 20H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h5l2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t94iyvbtl) {
  stroke-opacity: 0.4;
  d: path("M16 14h4v4m0-4l-6 6");
}

</style>
