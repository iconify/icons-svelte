<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bw1t57bti"/><path class="p1o66tbln"/><path class="hwufvfb8q"/><path class="y7d5mpfbz"/><path class="y334m4yqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-front-duotone-thin" {...props}></Icon>
<style>
:global(.bw1t57bti) {
  fill: currentColor;
  d: path("M3 20v-8l9 -9 9 9v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwufvfb8q) {
  d: path("M3 20v-8l9 -9 9 9v8Z");
}

:global(.p1o66tbln) {
  fill: currentColor;
  d: path("M9 8h6v4H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y334m4yqh) {
  d: path("M9 8h6v4H9Z");
}

:global(.y7d5mpfbz) {
  d: path("M10 20v-5h4v5");
}

</style>
