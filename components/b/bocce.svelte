<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtozhzawe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bocce" {...props}></Icon>
<style>
:global(.dtozhzawe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m11 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M8.5 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
