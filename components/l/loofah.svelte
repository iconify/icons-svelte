<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qo-wxdh9d"/><path class="xabw3fv9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:loofah" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qo-wxdh9d) {
  d: path("M4 13.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

:global(.xabw3fv9h) {
  d: path("M10 5.75C9 2 15 2 14 5.75M8 10.5q2-1.5 4 0t4 0m-9 3q2.5-1.5 5 0t5 0m-9 3q2-1.5 4 0t4 0");
}

</style>
