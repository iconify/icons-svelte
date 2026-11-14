<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqc71abqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:byline-check" {...props}></Icon>
<style>
:global(.pqc71abqn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-2 12c0-3.5 2.5-5.5 5.5-5.5c1.737 0 3.306.67 4.32 1.914M16.5 10h5m-6.75 8l2 2L21 15.75");
}

</style>
