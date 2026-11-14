<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hevwp4d0d"/><path class="ne7hynbjc"/><path class="oby6q9owa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ball-pit" {...props}></Icon>
<style>
:global(.hevwp4d0d) {
  d: path("M2.5 13h19M4 13v4.5A2.5 2.5 0 0 0 6.5 20h11a2.5 2.5 0 0 0 2.5-2.5V13");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ne7hynbjc) {
  d: path("M7 10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.oby6q9owa) {
  d: path("M9.5 6.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
