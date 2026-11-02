<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kx3gmwbow"/><path class="h6v8-8bsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:graduation-cap-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h6v8-8bsj) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m20 10l-8 4l-8-4l8-4zM8 12v4c0 1.105 1.79 2 4 2s4-.895 4-2v-4m4-2v5");
}

:global(.kx3gmwbow) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16 12v4c0 1.105-1.791 2-4 2s-4-.895-4-2v-4l-4-2l8-4l8 4Z");
}

</style>
