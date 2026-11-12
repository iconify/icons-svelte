<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dg92_ciox"/><path class="zno29s8sw"/><path class="s1rkwjrif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:equal-broken" {...props}></Icon>
<style>
:global(.dg92_ciox) {
  d: path("M4 9H12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s1rkwjrif) {
  d: path("M4 15H20");
}

:global(.zno29s8sw) {
  d: path("M16 9H20");
}

</style>
