<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m6rz7zcqn"/><path class="k7d35bvtx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:frost-warning" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k7d35bvtx) {
  d: path("M13.12 9.88L14 9l.88.88m3.13 5.41l.32 1.21l-1.21.32m-6.24 0l-1.21-.32l.32-1.21");
}

:global(.m6rz7zcqn) {
  d: path("M3 21V8a5 5 0 0 1 5-5h13m-7 5v12m5.2-9L8.8 17m10.4 0L8.8 11");
}

</style>
