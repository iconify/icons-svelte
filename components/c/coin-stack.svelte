<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="l61oyf3lf"/><path class="hymgq-ofz"/><rect class="uvb1rhbai"/><path class="smvttv9po"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coin-stack" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hymgq-ofz) {
  d: path("M2.75 10h8.5m-8.5 3.75h8.5m-8.5 3.75h8.5");
}

:global(.l61oyf3lf) {
  width: 8.5px;
  height: 15px;
  x: 2.75px;
  y: 6.25px;
  rx: 2px;
}

:global(.smvttv9po) {
  d: path("M13.75 17.5h7.5");
}

:global(.uvb1rhbai) {
  width: 7.5px;
  height: 7.5px;
  x: 13.75px;
  y: 13.75px;
  rx: 2px;
}

</style>
