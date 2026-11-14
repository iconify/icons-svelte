<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o314tvbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:logic-gate-or" {...props}></Icon>
<style>
:global(.o314tvbnr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 5H10c5 0 8 3.5 9.5 7c-1.5 3.5-4.5 7-9.5 7H5.5c2-3 2-11 0-14Zm-3 4h4m-4 6h4");
}

</style>
