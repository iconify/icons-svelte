<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="o2tws2j4q"/><path class="czw71esur"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:audio-track" {...props}></Icon>
<style>
:global(.czw71esur) {
  d: path("M6.5 11v2m3-4v6m3-5v4m3-5v6m3-4v2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o2tws2j4q) {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 6px;
  rx: 2.5px;
}

</style>
