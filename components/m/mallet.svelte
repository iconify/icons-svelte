<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bo_s7_bmn"/><path class="d-jylwbze"/><rect class="x5-j0-wxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mallet" {...props}></Icon>
<style>
:global(.bo_s7_bmn) {
  width: 16.5px;
  height: 7.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.d-jylwbze) {
  d: path("M7.75 5v3m8.5-3v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x5-j0-wxl) {
  width: 3px;
  height: 11px;
  x: 10.5px;
  y: 10.25px;
  rx: 1.5px;
}

</style>
