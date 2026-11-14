<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skh3l8lzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:physiotherapy-clinic" {...props}></Icon>
<style>
:global(.skh3l8lzc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m1.5 4L11 14m0 0l5 2v5m-5-7l-5.5 6.5m6.75-10.75l5.5.5");
}

</style>
