<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7380o3gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:puzzle-sharp" {...props}></Icon>
<style>
:global(.g7380o3gn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 7.25h2.5a2.5 2.5 0 1 1 4.5 0h4.5v4.5a2.5 2.5 0 1 1 0 4.5v4.5H3.25V7.25z");
}

</style>
