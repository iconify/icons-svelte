<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j2lx7tb_b"/><path class="dbt793l7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:redo" {...props}></Icon>
<style>
:global(.dbt793l7s) {
  d: path("m15.5 5.5l4 4l-4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2lx7tb_b) {
  d: path("M19.5 9.5h-10a5 5 0 0 0 0 10H15");
}

</style>
