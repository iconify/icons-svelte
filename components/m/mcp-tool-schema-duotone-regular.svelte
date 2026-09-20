<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pux-8e3tz"/><path class="cacmi2bmi"/><path class="ie2eafbvn"/><path class="ug4kkubvk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-tool-schema-duotone-regular" {...props}></Icon>
<style>
:global(.cacmi2bmi) {
  d: path("M13 3H9L6 6v15h12V8");
}

:global(.ie2eafbvn) {
  d: path("m11 9 -3 3 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pux-8e3tz) {
  fill: currentColor;
  d: path("M13 3H9L6 6v15h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ug4kkubvk) {
  d: path("m13 9 3 3 -3 3");
}

</style>
