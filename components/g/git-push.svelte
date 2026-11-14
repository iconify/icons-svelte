<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t72moub7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:git-push" {...props}></Icon>
<style>
:global(.t72moub7n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h14m-7 13V6.5M7.5 11L12 6.5l4.5 4.5m-7 7.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
