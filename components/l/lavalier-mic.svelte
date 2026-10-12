<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mjyvekbeh"/><rect class="oforz1p-a"/><path class="w2wdp0bfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lavalier-mic" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mjyvekbeh) {
  width: 5.5px;
  height: 7.5px;
  x: 9.25px;
  y: 2.75px;
  rx: 2.75px;
}

:global(.oforz1p-a) {
  width: 7.5px;
  height: 4px;
  x: 8.25px;
  y: 10.25px;
  rx: 1.25px;
}

:global(.w2wdp0bfb) {
  d: path("M12 14.25v4.5a2.5 2.5 0 0 1-2.5 2.5H2.75");
}

</style>
