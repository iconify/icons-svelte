<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g26tobccd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dehaze" {...props}></Icon>
<style>
:global(.g26tobccd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13L9 3.5l4.25 6l2.5-3L21.5 13M3 16.75q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0M3 20.5q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
