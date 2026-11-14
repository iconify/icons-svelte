<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpyspcjei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:artboard-multiple" {...props}></Icon>
<style>
:global(.lpyspcjei) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5h8v6h-8Zm11 0h8v6h-8Zm-11 9h8v6h-8Zm11 0h8v6h-8ZM2.5 2.75h4m7 0h4");
}

</style>
