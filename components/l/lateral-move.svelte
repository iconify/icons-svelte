<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucww4h8ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lateral-move" {...props}></Icon>
<style>
:global(.ucww4h8ot) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.25h7V21.5h-7Zm12 0h7V21.5h-7ZM4.5 6h15M17 3.5L19.5 6L17 8.5");
}

</style>
