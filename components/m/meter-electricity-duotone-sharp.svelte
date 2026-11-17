<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ckjqj_b3x"/><path class="g7wdqsbms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:meter-electricity-duotone-sharp" {...props}></Icon>
<style>
:global(.ckjqj_b3x) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 3h14v18H5Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g7wdqsbms) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3h14v18H5Zm-2 9h2m14 0h2m-8-4l-3 4h4l-3 4");
}

</style>
