<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wb_0sk4yy"/><path class="a4_-7ff2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-upload-duotone-sharp" {...props}></Icon>
<style>
:global(.a4_-7ff2t) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4h16v13H4Zm5 16h6m0-10l-3-3l-3 3m3-3v7");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.wb_0sk4yy) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 4h16v13H4Z");
}

</style>
