<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7we0kbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bubble-tea-shop" {...props}></Icon>
<style>
:global(.j7we0kbfi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9h14l-1.5 12.5h-11Zm0 0a7 4 0 0 1 14 0m-6-4l3-3M9.5 17h.01M12 18.5h.01M14.5 17h.01");
}

</style>
