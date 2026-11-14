<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2hczeb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:book-pile" {...props}></Icon>
<style>
:global(.f2hczeb6h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15.5h18V21H3ZM4.5 10H20v5.5H4.5Zm.871-5.652l12.873-1.809l.626 4.456L5.997 8.804ZM17 18.25h4m-16.5-5.5h4");
}

</style>
