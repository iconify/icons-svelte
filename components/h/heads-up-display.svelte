<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcut5gbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heads-up-display" {...props}></Icon>
<style>
:global(.rcut5gbfe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8q9.5-4 19 0v5q0 4.5-4.5 4.5H7q-4.5 0-4.5-4.5ZM7 11.5h5m4 0h.01");
}

</style>
