<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnslg1a_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bio-link-sharp" {...props}></Icon>
<style>
:global(.qnslg1a_k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 4.75h17.5M3.25 9h11M10 18.75H8a2.75 2.75 0 0 1 0-5.5h2m4 0h2a2.75 2.75 0 0 1 0 5.5h-2M9.5 16h5");
}

</style>
