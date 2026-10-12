<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zo-pglouc"/><rect class="hlut1ob9o"/><rect class="q50ovcblk"/><path class="d6pj2ebvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:extension-block" {...props}></Icon>
<style>
:global(.d6pj2ebvr) {
  d: path("m18.13 3.38l2.49 2.49q.88.88 0 1.76l-2.49 2.49q-.88.88-1.76 0l-2.49-2.49q-.88-.88 0-1.76l2.49-2.49q.88-.88 1.76 0");
}

:global(.hlut1ob9o) {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q50ovcblk) {
  width: 8px;
  height: 8px;
  x: 13.25px;
  y: 13.25px;
  rx: 1.75px;
}

:global(.zo-pglouc) {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.75px;
}

</style>
