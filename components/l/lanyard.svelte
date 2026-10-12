<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ooforrb2b"/><rect class="i5kxk2lww"/><path class="rzwey0j4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lanyard" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i5kxk2lww) {
  width: 11.5px;
  height: 9px;
  x: 6.25px;
  y: 12.25px;
  rx: 2px;
}

:global(.ooforrb2b) {
  d: path("m5.75 2.75l6.25 8.5l6.25-8.5");
}

:global(.rzwey0j4u) {
  d: path("M10.5 15.25h3m-4.25 3h5.5");
}

</style>
