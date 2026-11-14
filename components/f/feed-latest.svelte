<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0w_w5rdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:feed-latest" {...props}></Icon>
<style>
:global(.t0w_w5rdy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h11.5v4H3Zm0 6.75h11.5v4H3ZM3 17h11.5v4H3Zm16.75-7V3m-2 2l2-2l2 2");
}

</style>
