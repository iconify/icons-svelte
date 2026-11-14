<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8vjp0bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:metro-sign" {...props}></Icon>
<style>
:global(.y8vjp0bde) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0m-1.5 0h13m-6.5 5v9m-3 0h6");
}

</style>
