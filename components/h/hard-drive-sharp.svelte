<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="bvt8apb2v"/><path class="ouw8s78nl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hard-drive-sharp" {...props}></Icon>
<style>
:global(.bvt8apb2v) {
  d: path("M2 11L5 4L19 4L22 11L22 20L2 20L2 11ZM2 11L22 11");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ouw8s78nl) {
  fill: currentColor;
  d: path("M19 15.5C19 16.3284 18.3284 17 17.5 17C16.6716 17 16 16.3284 16 15.5C16 14.6716 16.6716 14 17.5 14C18.3284 14 19 14.6716 19 15.5Z");
  stroke: none;
}

</style>
