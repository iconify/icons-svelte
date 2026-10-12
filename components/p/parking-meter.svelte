<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mkottk0cv"/><path class="m3i8hg_zf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parking-meter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m3i8hg_zf) {
  d: path("M9 8.5a3 3 0 0 1 6 0m-3 0L13.5 7M12 12.75v8.5m-3 0h6");
}

:global(.mkottk0cv) {
  width: 10.5px;
  height: 10px;
  x: 6.75px;
  y: 2.75px;
  rx: 3.5px;
}

</style>
