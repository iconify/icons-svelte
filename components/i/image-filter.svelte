<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fr9wc8ere"/><circle class="xrii8hxli"/><path class="ryab5cbdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:image-filter" {...props}></Icon>
<style>
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

:global(.ryab5cbdq) {
  d: path("M12 7.25a4.75 4.75 0 0 0 0 9.5Z");
}

:global(.xrii8hxli) {
  cx: 12px;
  cy: 12px;
  r: 4.75px;
}

</style>
