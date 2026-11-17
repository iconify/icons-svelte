<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b_5suczoi"/><path class="kepmwvn2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-share-duotone" {...props}></Icon>
<style>
:global(.b_5suczoi) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 16A8.944 8.944 0 0 1 18.325 5.675A8.944 8.944 0 0 1 8 20l-5 1Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.kepmwvn2t) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16a8.944 8.944 0 1 1 4 4l-5 1Zm4-1v-1a2 2 0 0 1 2-2h6m-3-3l3 3l-3 3");
}

</style>
