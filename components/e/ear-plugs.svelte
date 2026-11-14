<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsgi95k5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ear-plugs" {...props}></Icon>
<style>
:global(.jsgi95k5p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16V7a3 3 0 0 1 6 0v9Zm11 0V7a3 3 0 0 1 6 0v9Zm-8 0q0 4.5 5.5 4.5t5.5-4.5");
}

</style>
