<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fg_a8lwva"/><path class="zt2ojnbyc"/><path class="epoh96bbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cricket-outline-thin" {...props}></Icon>
<style>
:global(.epoh96bbt) {
  d: path("M16 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fg_a8lwva) {
  d: path("M6 3h6v11H6Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zt2ojnbyc) {
  d: path("M9 14v7");
}

</style>
