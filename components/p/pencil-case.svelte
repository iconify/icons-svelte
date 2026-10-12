<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="aa63mgb4a"/><path class="ztpg_3b0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pencil-case" {...props}></Icon>
<style>
:global(.aa63mgb4a) {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 9.25px;
  rx: 3.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ztpg_3b0w) {
  d: path("M6.25 8.5v-2q0-.75.34-1.42l.82-1.66q.34-.67.68 0l.82 1.66q.34.67.34 1.42v2q0 .75-.75.75H7q-.75 0-.75-.75m-3.5 4.75h18.5m-5.5 0v3m-9.5-10.5h3");
}

</style>
