<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw79kebcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:golf-swing" {...props}></Icon>
<style>
:global(.fw79kebcg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M4 21c0-4 3.5-6.5 8-6.5s8 2.5 8 6.5m-3.5-5.5l4.5-11m0 0l-2.25-1");
}

</style>
