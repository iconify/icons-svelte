<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="clhdcdczn"/><rect class="oqts0u5ld"/><path class="m_b_1zbbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:one-hand-mode" {...props}></Icon>
<style>
:global(.clhdcdczn) {
  d: path("M5.75 12.5V5.25a2.5 2.5 0 0 1 2.5-2.5h7.5a2.5 2.5 0 0 1 2.5 2.5v7.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m_b_1zbbn) {
  d: path("M12 5.25v3.5M10.25 7L12 8.75L13.75 7");
}

:global(.oqts0u5ld) {
  width: 12.5px;
  height: 10.25px;
  x: 5.75px;
  y: 11px;
  rx: 2.5px;
}

</style>
