<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxx20dbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nps" {...props}></Icon>
<style>
:global(.hxx20dbpq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16.75a9.5 9.5 0 0 1 19 0m-9.5 0l4.5-4.5m-4.5 4.5h.01");
}

</style>
