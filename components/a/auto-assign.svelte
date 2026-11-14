<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsxqqpczq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:auto-assign" {...props}></Icon>
<style>
:global(.dsxqqpczq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.672 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.758 0 1.468.093M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11 14.5v-3m0 0l-3-3m3 3l3-3m-2 0h2v2");
}

</style>
