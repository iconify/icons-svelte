<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a8qz153ka"/><path class="w4onmpb6s"/><path class="zuwyzt6-u"/><path class="v8xtwkb5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hammer-tool-duotone-regular" {...props}></Icon>
<style>
:global(.a8qz153ka) {
  fill: currentColor;
  d: path("M10 6h7v4h-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v8xtwkb5y) {
  d: path("M10 6c-2 1 -3 3 -3 4");
}

:global(.w4onmpb6s) {
  d: path("M10 6h7v4h-7Z");
}

:global(.zuwyzt6-u) {
  d: path("M13 10v12");
}

</style>
