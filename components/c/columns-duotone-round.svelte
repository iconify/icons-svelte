<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f9znh2twl"/><path class="jeke5b99r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:columns-duotone-round" {...props}></Icon>
<style>
:global(.f9znh2twl) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 7v10a3 3 0 1 1-6 0V7a3 3 0 1 1 6 0m10 0v10a3 3 0 1 1-6 0V7a3 3 0 1 1 6 0");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jeke5b99r) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 7a3 3 0 0 1 6 0v10a3 3 0 0 1-6 0Zm10 0a3 3 0 0 1 6 0v10a3 3 0 0 1-6 0Z");
}

</style>
