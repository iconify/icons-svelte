<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xiu0i0b4m"/><path class="t752qkbva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lounge-area" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t752qkbva) {
  d: path("M2.5 12.5a2 2 0 0 1 4 0V14h11v-1.5a2 2 0 0 1 4 0V17a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 17Zm2.5 6v2m14-2v2M12 14v4.5");
}

:global(.xiu0i0b4m) {
  d: path("M4.5 10.5V6A2.5 2.5 0 0 1 7 3.5h10A2.5 2.5 0 0 1 19.5 6v4.5");
}

</style>
