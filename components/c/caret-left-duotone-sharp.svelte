<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h98qfj0yp"/><path class="d4l4jfd5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:caret-left-duotone-sharp" {...props}></Icon>
<style>
:global(.d4l4jfd5o) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 8l-4 4l4 4Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h98qfj0yp) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 8v8l-4-4Z");
}

</style>
