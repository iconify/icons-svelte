<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z41hf4b9g"/><path class="i4ddl5bmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ice-tray" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i4ddl5bmk) {
  d: path("M3.75 16.25h16.5m-8.25-5v10m1.57-17.9l2.16-.45q1.17-.25 1.42.92l.45 2.16q.25 1.17-.92 1.42l-2.16.45q-1.17.25-1.42-.92l-.45-2.16q-.25-1.17.92-1.42");
}

:global(.z41hf4b9g) {
  width: 16.5px;
  height: 10px;
  x: 3.75px;
  y: 11.25px;
  rx: 2px;
}

</style>
