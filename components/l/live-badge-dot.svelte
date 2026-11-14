<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg-a6abkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:live-badge-dot" {...props}></Icon>
<style>
:global(.dg-a6abkj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8.464 8.464a5 5 0 0 1 7.072 0m0 7.072a5 5 0 0 1-7.072 0m-2.828-9.9a9 9 0 0 1 12.728 0m0 12.728a9 9 0 0 1-12.728 0");
}

</style>
