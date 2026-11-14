<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqlkc8yjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:demand-spike" {...props}></Icon>
<style>
:global(.nqlkc8yjb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 19h5l2-7l2 7l2-15l2 15h5");
}

</style>
