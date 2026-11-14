<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v20idkbkv"/><path class="s11iokb2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:placer-mine" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s11iokb2d) {
  d: path("M8.25 14.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0m5.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0M11 10.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

:global(.v20idkbkv) {
  d: path("M2.5 6h2c1 8.5 3 12 7.5 12s6.5-3.5 7.5-12h2");
}

</style>
