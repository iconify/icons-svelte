<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c92xfhcsq"/><path class="qothvdbsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:door-sharp-fill" {...props}></Icon>
<style>
:global(.c92xfhcsq) {
  fill: currentColor;
  d: path("M5 22L5 3C5 2.4477 5.4477 2 6 2L18 2C18.5523 2 19 2.4477 19 3L19 22L5 22ZM15 10L13 10L13 14L15 14L15 10Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qothvdbsj) {
  d: path("M1 21L23 21");
}

</style>
