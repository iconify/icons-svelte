<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kacbmpbqo"/><path class="quhs-mbly"/><path class="sz876h5gv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:delivery-tip" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kacbmpbqo) {
  d: path("M2.5 13.5L5 16v5.5h14V16l2.5-2.5");
}

:global(.quhs-mbly) {
  d: path("M6.25 7.75a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0M5 16h14");
}

:global(.sz876h5gv) {
  d: path("M13.75 5.75h-2.5a1 1 0 0 0 0 2h1.5a1 1 0 0 1 0 2h-2.5M12 4.25v1.5m0 4v1.5");
}

</style>
