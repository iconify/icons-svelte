<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mn3dzebek"/><path class="ftyha7-_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:android-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ftyha7-_g) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 9L6 6m10 3l2-3M8 13h.01M16 13h.01M3 17a9 9 0 0 1 18 0z");
}

:global(.mn3dzebek) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 18H3a1 1 0 0 1-1-1C2 11.477 6.477 7 12 7s10 4.477 10 10a1 1 0 0 1-1 1");
}

</style>
