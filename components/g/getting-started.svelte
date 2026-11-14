<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x68w8zb4x"/><path class="t6-u3v5du"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:getting-started" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t6-u3v5du) {
  d: path("m8.25 10.5l-2.75 3v3L8 15m7.75-4.5l2.75 3v3L16 15m-5.25 0L12 18.25L13.25 15M4.5 21h15");
}

:global(.x68w8zb4x) {
  d: path("M12 2.5c3.5 2.25 4.5 6 4 12.5H8c-.5-6.5.5-10.25 4-12.5");
}

</style>
