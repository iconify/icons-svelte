<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_yefvb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:punching-bag-sharp" {...props}></Icon>
<style>
:global(.s_yefvb1w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 7.75h10.5v13.5H6.75zm0 3.25h10.5m-10.5 7h10.5M12 2.75v2.5m-3.25 2.5L12 5.25l3.25 2.5");
}

</style>
