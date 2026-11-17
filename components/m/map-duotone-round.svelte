<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ve_yuo1cp"/><path class="h7bf-rbgv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-duotone-round" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h7bf-rbgv) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 3l6 3l2-1c1.838-.919 4 .162 4 2v9c0 1.226-.774 2.387-2 3l-4 2l-6-3l-2 1c-1.838.919-4-.162-4-2V8c0-1.226.774-2.387 2-3zm0 0v15m6-12v15");
}

:global(.ve_yuo1cp) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 3v15l-2 1c-1.838.919-4-.162-4-2V8c.001-1.305.863-2.431 2-3Zm6 3l2-1c1.838-.919 4 .162 4 2v9c-.001 1.305-.863 2.431-2 3l-4 2Z");
}

</style>
