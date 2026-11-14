<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv4nx3b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:communion-bread" {...props}></Icon>
<style>
:global(.nv4nx3b9z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 9a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m-3 9c1.5 3 17.5 3 19 0ZM12 5.5v7M9.5 8h5");
}

</style>
