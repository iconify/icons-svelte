<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw3hiccsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:goalie-stick" {...props}></Icon>
<style>
:global(.xw3hiccsb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20 3l-3.5 8M15 10l3 1.5l-4.5 9.5h-8a1.5 1.5 0 0 1 0-3H11Z");
}

</style>
