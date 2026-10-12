<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kf6usrblm"/><path class="ijs0p36kx"/><rect class="owi0voakq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:overdraft" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ijs0p36kx) {
  d: path("M2.75 12h18.5");
}

:global(.kf6usrblm) {
  width: 5px;
  height: 4.25px;
  x: 4.25px;
  y: 4.75px;
  rx: 1px;
}

:global(.owi0voakq) {
  width: 5px;
  height: 6.25px;
  x: 14.75px;
  y: 15px;
  rx: 1px;
}

</style>
