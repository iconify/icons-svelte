<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sht6hbb9p"/><rect class="oss_qbbcs"/><path class="haz4ihblf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fuse-box" {...props}></Icon>
<style>
:global(.haz4ihblf) {
  d: path("M8.75 12L10 10l2 4l2-4l1.25 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oss_qbbcs) {
  width: 12.5px;
  height: 10px;
  x: 5.75px;
  y: 7px;
  rx: 2.5px;
}

:global(.sht6hbb9p) {
  d: path("M2.75 5.75v12.5m18.5-12.5v12.5");
}

</style>
