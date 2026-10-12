<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhclxacbk"/><rect class="p7fqmbcmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:distribute-vertical" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p7fqmbcmq) {
  width: 12.5px;
  height: 6px;
  x: 5.75px;
  y: 9px;
  rx: 1.5px;
}

:global(.zhclxacbk) {
  d: path("M2.75 3.75h18.5m-18.5 16.5h18.5");
}

</style>
