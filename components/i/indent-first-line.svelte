<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f728zh8cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:indent-first-line" {...props}></Icon>
<style>
:global(.f728zh8cj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 4.5h9m-17 5h17m-17 5h17m-17 5H14M3.5 4.5H8M6.25 2.75L8 4.5L6.25 6.25");
}

</style>
