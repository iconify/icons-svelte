<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vwuabktpy"/><path class="dm_wopyrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:child-safe-cap" {...props}></Icon>
<style>
:global(.dm_wopyrf) {
  d: path("M16.5 17.5v-1a1.5 1.5 0 0 1 3 0v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vwuabktpy) {
  d: path("M2.5 2.5h16v5h-16ZM12.2 20H3V7.5h15v4.7m-7.5-.95v5M8 13.75h5m2 3.75h6v4h-6Z");
}

</style>
