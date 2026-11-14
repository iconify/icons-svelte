<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu38jgbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:line-numbers" {...props}></Icon>
<style>
:global(.nu38jgbvl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5L5 3v6.5M3 14a2 2 0 1 1 3.5 1.5l-3.5 5h4m2.5-18v19m3-16h8m-8 6.5h6m-6 6.5H20");
}

</style>
