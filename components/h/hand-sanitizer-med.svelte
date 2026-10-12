<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="c3-v0cbih"/><path class="k0lmxfv7q"/><rect class="bb3ds174x"/><path class="jr3j-3brv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hand-sanitizer-med" {...props}></Icon>
<style>
:global(.bb3ds174x) {
  width: 3.5px;
  height: 2.75px;
  x: 8.75px;
  y: 7.5px;
  rx: 0.75px;
}

:global(.c3-v0cbih) {
  width: 11.5px;
  height: 11px;
  x: 4.75px;
  y: 10.25px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jr3j-3brv) {
  d: path("M10.5 7.5V3.75h5.75m2.5 2.75c.9 1.2 1.5 2 1.5 2.8a1.5 1.5 0 0 1-3 0c0-.8.6-1.6 1.5-2.8");
}

:global(.k0lmxfv7q) {
  d: path("M10.5 13.5V18m-2.25-2.25h4.5");
}

</style>
