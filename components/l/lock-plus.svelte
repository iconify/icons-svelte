<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="harne1byn"/><path class="qeudbmb6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lock-plus" {...props}></Icon>
<style>
:global(.harne1byn) {
  width: 14.5px;
  height: 10.5px;
  x: 4.75px;
  y: 10.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qeudbmb6i) {
  d: path("M7.75 10.75V7.5a4.25 4.25 0 0 1 8.5 0v3.25m-4.25 4v2.5");
}

</style>
