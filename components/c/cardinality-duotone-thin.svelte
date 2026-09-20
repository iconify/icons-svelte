<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ziqm699pb"/><path class="nzus6ybfu"/><path class="v4_esibhq"/><path class="ujr228b1o"/><path class="x8lnyu1_x"/><path class="r0uia_bgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cardinality-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nzus6ybfu) {
  fill: currentColor;
  d: path("M13 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r0uia_bgu) {
  d: path("M19 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ujr228b1o) {
  d: path("M3 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.v4_esibhq) {
  fill: currentColor;
  d: path("M19 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x8lnyu1_x) {
  d: path("M13 14a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.ziqm699pb) {
  fill: currentColor;
  d: path("M3 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
