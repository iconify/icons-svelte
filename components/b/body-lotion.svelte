<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dcoewqb0r"/><rect class="wjugozbax"/><path class="yyol2gwzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:body-lotion" {...props}></Icon>
<style>
:global(.dcoewqb0r) {
  d: path("M7.5 8V2.75m-2.5 0h5.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wjugozbax) {
  width: 9.5px;
  height: 13.25px;
  x: 2.75px;
  y: 8px;
  rx: 3.25px;
}

:global(.yyol2gwzp) {
  d: path("M5.5 15.5h4m4.25 5.75h6.5a2.4 2.4 0 0 0-1.85-2.9A2.4 2.4 0 0 0 15.5 16c-1.15.85-1.75 2.75-1.75 5.25");
}

</style>
