<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s1xj6jveq"/><rect class="w-_h-kbom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:capo" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s1xj6jveq) {
  d: path("M8.5 2.75v6.5m0 5.5v6.5m7-18.5v6.5m0 5.5v6.5M8.5 5.5h7m-7 13h7");
}

:global(.w-_h-kbom) {
  width: 15.5px;
  height: 5.5px;
  x: 4.25px;
  y: 9.25px;
  rx: 2px;
}

</style>
