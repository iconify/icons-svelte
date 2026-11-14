<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kvs-dquzx"/><path class="hx1kbhufm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:foot-side" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hx1kbhufm) {
  d: path("M16.25 15.25q1 1 .75 2.25");
}

:global(.kvs-dquzx) {
  d: path("M6.5 2.5v9q-3 2.25-3 6c0 2 1.5 3 3.5 3h11.5c2 0 2.75-1.75 2-3s-2.5-1.75-5-2.5s-4-2.5-4-5V2.5");
}

</style>
