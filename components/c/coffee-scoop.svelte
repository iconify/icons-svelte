<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7rflbwzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coffee-scoop" {...props}></Icon>
<style>
:global(.x7rflbwzl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 6.75h10v4a5 5 0 0 1-5 5a5 5 0 0 1-5-5Zm0 3l-7.5 7.5");
}

</style>
