<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hfb8w9b7u"/><path class="c_38-1b9y"/><path class="twev6kbji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:jam-jar" {...props}></Icon>
<style>
:global(.c_38-1b9y) {
  d: path("M6 10h12v8.5a2.75 2.75 0 0 1-2.75 2.75h-6.5A2.75 2.75 0 0 1 6 18.5Z");
}

:global(.hfb8w9b7u) {
  width: 13.5px;
  height: 4px;
  x: 5.25px;
  y: 3px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.twev6kbji) {
  d: path("M9.5 15.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
