<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="npenpvb6u"/><path class="ibuanu9pl"/><path class="t917aebob"/><path class="zml9_hk2z"/><path class="hf_gtezns"/><path class="tgth1rbuy"/><path class="lzdsnnb7v"/><path class="ydp7-vbsy"/><path class="rod9nhbdx"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:noise-inject-duotone-thin" {...props}></Icon>
<style>
:global(.hf_gtezns) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ibuanu9pl) {
  fill: currentColor;
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lzdsnnb7v) {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.npenpvb6u) {
  fill: currentColor;
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rod9nhbdx) {
  d: path("m10 12.5 2 2 2 -2");
}

:global(.t917aebob) {
  fill: currentColor;
  d: path("M16 4.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tgth1rbuy) {
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

:global(.ydp7-vbsy) {
  d: path("M16 4.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zml9_hk2z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 12.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
