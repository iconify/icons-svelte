<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="urfuvbcjk"/><rect class="ve-22ccky"/><rect class="x01a8-d8q"/><path class="zd7hxcctd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:razor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.urfuvbcjk) {
  d: path("M5 2.75h14");
}

:global(.ve-22ccky) {
  width: 16.5px;
  height: 3.5px;
  x: 3.75px;
  y: 5px;
  rx: 1.5px;
}

:global(.x01a8-d8q) {
  width: 3.5px;
  height: 10.5px;
  x: 10.25px;
  y: 10.75px;
  rx: 1.75px;
}

:global(.zd7hxcctd) {
  d: path("M10.25 14.5h3.5m-3.5 2.5h3.5");
}

</style>
