<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugjw1m8br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:braille" {...props}></Icon>
<style>
:global(.ugjw1m8br) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9 0h.01M6.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-5 7h.01m4.99 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
