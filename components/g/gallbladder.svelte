<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qovl_if8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gallbladder" {...props}></Icon>
<style>
:global(.qovl_if8n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6.25c0-2 1.25-2.75 3-2.75h11.25c1.5 0 2.25 1.25 1.75 2.75c-1.75 3-4.75 6.75-9 8.5c-2.25.75-4.75.75-6.25-1c-.5-1.25-.75-4.5-.75-7.5Zm10.5 7.5c1.75.75 2.5 3.5 1.75 5.5s-3 2.5-3.75 1s.25-4.5 2-6.5Zm-1-6.25L11 11");
}

</style>
