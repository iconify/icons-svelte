<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1-ltznca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:group-shelter" {...props}></Icon>
<style>
:global(.q1-ltznca) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9L12 3l9.5 6Zm3 0v12m13-12v12m-10-5h7m-5.75 0v4.5m4.5-4.5v4.5");
}

</style>
