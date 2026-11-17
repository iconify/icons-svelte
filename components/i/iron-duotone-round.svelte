<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lkij6pbxi"/><path class="u8l34t4ny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:iron-duotone-round" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lkij6pbxi) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 14a4 4 0 0 1-4 4H5c-.738 0-1.369-.631-1-1l5-5c.764-.763 1.959-1 3-1h9Z");
}

:global(.u8l34t4ny) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 11v3a4 4 0 0 1-4 4H5c-.738 0-1.369-.631-1-1l5-5c.64-.64 1.72-1 3-1zm0 0V8a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v3");
}

</style>
