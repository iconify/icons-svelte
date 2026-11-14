<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j0h368bpl"/><path class="mciu6vb7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-layer-parking" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j0h368bpl) {
  d: path("M3 3v18h18V3");
}

:global(.mciu6vb7x) {
  d: path("M7.5 11L9 7h6l1.5 4m-7.875 0h6.75A2.625 2.625 0 0 1 18 13.625v.75A2.625 2.625 0 0 1 15.375 17h-6.75A2.625 2.625 0 0 1 6 14.375v-.75A2.625 2.625 0 0 1 8.625 11m.125 3h.01m6.49 0h.01");
}

</style>
