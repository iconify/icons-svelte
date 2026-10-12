<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izeczmu8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:acorn-sharp" {...props}></Icon>
<style>
:global(.izeczmu8j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 11h11v.75c0 4.5-2.5 8.25-5.5 9.5c-3-1.25-5.5-5-5.5-9.5ZM5 11c0-3 3-5 7-5s7 2 7 5Zm7-5V3.8l1.75-1.05");
}

</style>
