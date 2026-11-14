<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t022q6bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:camping-allowed" {...props}></Icon>
<style>
:global(.t022q6bcp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.286 19.5H3l9-15l6.126 10.21M12 12v4.8m0 2.4v.3m2.75-1.5l2 2L21 15.75");
}

</style>
