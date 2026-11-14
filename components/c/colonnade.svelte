<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq8gx7b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:colonnade" {...props}></Icon>
<style>
:global(.sq8gx7b0g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19v3.5h-19ZM4 6.5h2.5V21H4Zm6.75 0h2.5V21h-2.5Zm6.75 0H20V21h-2.5Z");
}

</style>
