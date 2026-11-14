<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x76ggnqox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:herbal-compress" {...props}></Icon>
<style>
:global(.x76ggnqox) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12.5L7.5 8h9L14 12.5c5 1.5 5.5 9-2 9s-7-7.5-2-9m-1.5 0h7M12 8V2.5m0 2.75c.5-2 2-2.75 4.5-2.75c-.5 2-2 2.75-4.5 2.75");
}

</style>
