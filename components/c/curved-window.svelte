<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob48qybzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:curved-window" {...props}></Icon>
<style>
:global(.ob48qybzz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3q9.5 3 19 0v12.5q-9.5-3-19 0Zm7.25 16.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
