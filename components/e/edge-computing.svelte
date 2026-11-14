<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1gzy1b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:edge-computing" {...props}></Icon>
<style>
:global(.h1gzy1b5i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 15H10a2.5 2.5 0 0 0 0-5a3.25 3.25 0 0 0-6 .5A2.25 2.25 0 0 0 5.75 15ZM14.5 4.5h7v15h-7Zm0 5h7m-7 5h7m-9-2.5h2");
}

</style>
