<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fr9wc8ere"/><rect class="d1csye2xg"/><path class="s__ukp43w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:modal" {...props}></Icon>
<style>
:global(.d1csye2xg) {
  width: 12px;
  height: 10px;
  x: 6px;
  y: 7.5px;
  rx: 2px;
}

:global(.fr9wc8ere) {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s__ukp43w) {
  d: path("M6.75 10.75h10.5m-2.5-2L16 10m0-1.25L14.75 10");
}

</style>
