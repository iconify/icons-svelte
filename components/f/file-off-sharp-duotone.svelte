<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g5ncw42dh"/><path class="p67huvb8z"/><path class="ahhqo1b4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-off-sharp-duotone" {...props}></Icon>
<style>
:global(.ahhqo1b4s) {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

:global(.g5ncw42dh) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 23H4C3.4477 23 3 22.5523 3 22V3L21 21V22C21 22.5523 20.5523 23 20 23H16Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p67huvb8z) {
  stroke-opacity: 0.4;
  d: path("M20 15.34L20 8L14 2L6.5 2M14 2L14 8L20 8");
}

</style>
