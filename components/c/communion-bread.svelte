<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="w5c3o5b4m"/><path class="e3g_p9bwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:communion-bread" {...props}></Icon>
<style>
:global(.e3g_p9bwk) {
  d: path("M12 5.25v7.25M9.5 7.75h5M2.75 19a9.25 2 0 1 0 18.5 0a9.25 2 0 1 0-18.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w5c3o5b4m) {
  cx: 12px;
  cy: 8.75px;
  r: 6px;
}

</style>
