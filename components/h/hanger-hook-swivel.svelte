<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kq87q8baz"/><path class="ww8s3yb2f"/><path class="ovafeep8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hanger-hook-swivel" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kq87q8baz) {
  d: path("M12 15.5V9a3 3 0 1 0-3-3M2.5 21l9.5-5.5l9.5 5.5z");
}

:global(.ovafeep8l) {
  d: path("m14 11l1.5 1.5l-1.75 1");
}

:global(.ww8s3yb2f) {
  d: path("M8.5 12.5a3.5 1.25 0 0 0 7 0");
}

</style>
