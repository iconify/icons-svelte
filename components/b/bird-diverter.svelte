<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e72z8u1sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bird-diverter" {...props}></Icon>
<style>
:global(.e72z8u1sj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5q9.5 3 19 0M12 6v2.5m-5 5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm0 0h10");
}

</style>
