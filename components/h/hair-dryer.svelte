<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xde9fv6nz"/><path class="c5yphdxdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hair-dryer" {...props}></Icon>
<style>
:global(.c5yphdxdu) {
  d: path("m12 12l.75 7a2 2 0 0 0 2 2h.5a2 2 0 0 0 2-2l.75-7m-5-4a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xde9fv6nz) {
  d: path("M11 5L3.5 6.5v3L11 11a5 5 0 1 0 0-6");
}

</style>
