<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c__mxzcyr"/><path class="i9t-8lpig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-keyhole-duotone-sharp" {...props}></Icon>
<style>
:global(.c__mxzcyr) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 9h16v12H4Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.i9t-8lpig) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9h16v12H4Zm7 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 1v2M8 9V7a4 4 0 1 1 8 0v2");
}

</style>
