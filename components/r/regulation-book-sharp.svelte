<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwdp2hb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:regulation-book-sharp" {...props}></Icon>
<style>
:global(.vwdp2hb6k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h13.5v18.5H3.75zm3.5 0v18.5M10 7h4.5m2.75-2h3.5v3.5h-3.5m0 2.5h3.5v3.5h-3.5");
}

</style>
