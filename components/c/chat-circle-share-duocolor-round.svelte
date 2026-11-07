<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ix18mnb1w"/><path class="n5iafhovj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-share-duocolor-round" {...props}></Icon>
<style>
:global(.ix18mnb1w) {
  stroke-opacity: 0.4;
  d: path("M8 15a3 3 0 0 1 3-3h5m-3-3l3 3l-3 3");
}

:global(.n5iafhovj) {
  d: path("M4 16a8.944 8.944 0 1 1 4 4l-5 1Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
