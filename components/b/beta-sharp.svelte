<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9fb2ybmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:beta-sharp" {...props}></Icon>
<style>
:global(.i9fb2ybmx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.5a4.75 4.75 0 0 1 9.5 0c0 2-1.5 3.5-3.5 3.5c2.75 0 4.75 1.75 4.75 4.25s-2 4.25-4.75 4.25c-2.25 0-4.25-1.25-6-3m0-9V21");
}

</style>
