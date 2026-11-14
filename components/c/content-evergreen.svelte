<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3vvbzbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:content-evergreen" {...props}></Icon>
<style>
:global(.u3vvbzbfm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l-4.5 6h2.25L5.5 14h2.75L4.5 18.5h15L15.75 14h2.75l-4.25-5.5h2.25Zm0 16v3m-5 0h10");
}

</style>
