<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pxkcm-fgs"/><rect class="mrul5m_rx"/><path class="adlvkbbsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boom-mic" {...props}></Icon>
<style>
:global(.adlvkbbsi) {
  d: path("M13.25 11.25h5.5m-5.5 3h5.5m-5.5 3h5.5M2.75 3v3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mrul5m_rx) {
  width: 5.5px;
  height: 14px;
  x: 13.25px;
  y: 7.25px;
  rx: 2.75px;
}

:global(.pxkcm-fgs) {
  d: path("M2.75 4.75H16m0 0v2.5");
}

</style>
