<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-_b1gq7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-grid" {...props}></Icon>
<style>
:global(.n-_b1gq7v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3v18M7.5 3v18M12 3v18m4.5-18v18M21 3v18M3 3h18M3 7.5h18M3 12h18M3 16.5h18M3 21h18");
}

</style>
