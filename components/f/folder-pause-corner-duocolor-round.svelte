<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="daaep74_v"/><path class="qravvf8eg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-pause-corner-duocolor-round" {...props}></Icon>
<style>
:global(.daaep74_v) {
  stroke-opacity: 0.4;
  d: path("M15 13v8m4-8v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qravvf8eg) {
  d: path("M12 6h7a2 2 0 0 1 2 2M8 20H7a4 4 0 0 1-4-4V6a2 2 0 0 1 2-2h5l2 2");
}

</style>
