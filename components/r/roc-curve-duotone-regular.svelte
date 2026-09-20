<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gb7yzvvzz"/><path class="szk-jdbiz"/><path class="q1h6kybti"/><path class="qe97cg-lx"/><path class="hj1fiqb-o"/><path class="bd3-a5q0s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:roc-curve-duotone-regular" {...props}></Icon>
<style>
:global(.bd3-a5q0s) {
  d: path("M6 18 18 6");
}

:global(.gb7yzvvzz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hj1fiqb-o) {
  d: path("M6 18v-6l6 -6h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q1h6kybti) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 18 18 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qe97cg-lx) {
  d: path("M3 3v18h18");
}

:global(.szk-jdbiz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 18v-6l6 -6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
