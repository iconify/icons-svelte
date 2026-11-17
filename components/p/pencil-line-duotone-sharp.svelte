<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vwh2dlb2y"/><path class="dn67hmb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-line-duotone-sharp" {...props}></Icon>
<style>
:global(.dn67hmb4z) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 20v-4L16 4l4 4L8 20zm8-12l4 4m-8 8h12");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.vwh2dlb2y) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 16L16 4l4 4L8 20H4Z");
}

</style>
