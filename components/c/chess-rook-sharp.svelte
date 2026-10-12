<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi-58ro9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chess-rook-sharp" {...props}></Icon>
<style>
:global(.yi-58ro9q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3h1.75v2h1.65V3h2.2v2h1.65V3H17v5l-.35.35l-.8.8l-.35.35v6h-7v-6l-.35-.35l-.8-.8L7 8V3zm1.25 6.5h6.5M5 18.5h14v2.75H5z");
}

</style>
