<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aupwjrbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:c-clamp" {...props}></Icon>
<style>
:global(.aupwjrbgo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 4h-7a4.5 4.5 0 0 0-4.5 4.5v7A4.5 4.5 0 0 0 10 20h7m0-17.5V13m-2 0h4M15 2.5h4M15 20h4");
}

</style>
