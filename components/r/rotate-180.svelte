<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gx7jiib5h"/><path class="tl51n0-xo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rotate-180" {...props}></Icon>
<style>
:global(.gx7jiib5h) {
  d: path("M3.5 15.5a8 8 0 0 1 16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tl51n0-xo) {
  d: path("m17 13l2.5 2.5L22 13m-10.5 2.5h.01");
}

</style>
