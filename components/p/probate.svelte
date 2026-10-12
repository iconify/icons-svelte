<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><path class="w5e5jnb7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:probate" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w5e5jnb7o) {
  d: path("M8.25 6.25h7.5m-6.93 6.26l2.61-2.27q.57-.49 1.14 0l2.61 2.27q.57.49.57 1.24v3.5q0 .75-.75.75H9q-.75 0-.75-.75v-3.5q0-.75.57-1.24M12 18v-2.25");
}

:global(.x00qgzx7x) {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
