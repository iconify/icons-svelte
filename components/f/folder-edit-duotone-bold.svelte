<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r0jamibkm"/><path class="bynfoybqk"/><path class="bn_pu6j-z"/><path class="z9eky33_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:folder-edit-duotone-bold" {...props}></Icon>
<style>
:global(.bn_pu6j-z) {
  d: path("M20 7v13H4V4h5l3 3h4");
}

:global(.bynfoybqk) {
  fill: currentColor;
  d: path("M8.5 17v-2.5l5 -5L16 12l-5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r0jamibkm) {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z9eky33_w) {
  d: path("M8.5 17v-2.5l5 -5L16 12l-5 5Z");
}

</style>
