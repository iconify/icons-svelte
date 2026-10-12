<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a8u166caj"/><path class="di9aaqbdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:microphone-stand" {...props}></Icon>
<style>
:global(.a8u166caj) {
  width: 5px;
  height: 7.5px;
  x: 9.5px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.di9aaqbdm) {
  d: path("M12 10.25v8.5m0 0l-5 2.5m5-2.5l5 2.5m-5-2.5v2.5M9.75 13h4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
