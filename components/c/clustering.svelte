<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-igxbbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clustering" {...props}></Icon>
<style>
:global(.g-igxbbbe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m9.5 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M5.75 8.75h.01m2.49-2.5h.01m6.99 10.5h.01m2.49-2.5h.01M19.5 5h.01");
}

</style>
