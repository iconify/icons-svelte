<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgrfb-bqu"/><path class="nooweob_o"/><path class="gmrzwr9af"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:attribution-outline-thin" {...props}></Icon>
<style>
:global(.gmrzwr9af) {
  d: path("M14 16a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nooweob_o) {
  d: path("M3 10h12");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
