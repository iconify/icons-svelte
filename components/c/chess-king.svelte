<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilqxmpbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chess-king" {...props}></Icon>
<style>
:global(.ilqxmpbkc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v6M9.75 4.75h4.5M7.5 8.5h9l-2.25 4l1.5 6h-7.5l1.5-6Zm-2 10h13v3h-13Z");
}

</style>
