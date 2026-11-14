<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbvm2pb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flash-red-eye" {...props}></Icon>
<style>
:global(.cbvm2pb5h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10c3.5-8 12-8 15.5 0c-3.5 8-12 8-15.5 0Zm7.75 0h.01m8.99 4.5L16 18.75h2.75L17.5 22l4-4.75h-2.75Z");
}

</style>
