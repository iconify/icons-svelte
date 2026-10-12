<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mvnog4ucf"/><path class="gwucx7bfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:image-caption" {...props}></Icon>
<style>
:global(.gwucx7bfe) {
  d: path("m5.75 12.25l3.5-3.75l2.5 2.5l2-2l3.5 3.25M5.75 18.5h12.5M8.5 21.25h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mvnog4ucf) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
