<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qxsbu8bvx"/><path class="hxssifbwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:laptop-doctor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hxssifbwx) {
  d: path("M10 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8.5 13c0-1.75 1.5-2.75 3.5-2.75s3.5 1 3.5 2.75m-4.25-6.75h.01");
}

:global(.qxsbu8bvx) {
  d: path("M6.125 3h11.75A2.625 2.625 0 0 1 20.5 5.625v6.75A2.625 2.625 0 0 1 17.875 15H6.125A2.625 2.625 0 0 1 3.5 12.375v-6.75A2.625 2.625 0 0 1 6.125 3M2 18h20");
}

</style>
