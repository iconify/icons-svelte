<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4qu_5bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:amino-acid" {...props}></Icon>
<style>
:global(.e4qu_5bqz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m7.25 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m7.25 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-7.25 9a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M7 7.5h2.75m4.5 0H17m-5 2.25v4.5");
}

</style>
