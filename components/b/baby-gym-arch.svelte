<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_y_xq2lv"/><path class="wec6fm33k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:baby-gym-arch" {...props}></Icon>
<style>
:global(.c_y_xq2lv) {
  d: path("M2.5 21.5V12a9.5 9.5 0 0 1 19 0v9.5M8 3.5v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wec6fm33k) {
  d: path("M5.5 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M16 3.5V9m-2.25 0h4.5");
}

</style>
