<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ie299ccst"/><path class="d9qim2bof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:remote-control-duotone-sharp" {...props}></Icon>
<style>
:global(.d9qim2bof) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3h10v18H7Zm5 0v2m-2 10h.01M14 15h.01M10 18h.01M14 18h.01M10 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ie299ccst) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 3h10v18H7Z");
}

</style>
