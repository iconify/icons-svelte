<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t970ugb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lip-sync-sharp" {...props}></Icon>
<style>
:global(.t970ugb1i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12c1.75-2.5 3.75-4 5-4h.5l.5.5l.5-.5h.5c1.25 0 3.25 1.5 5 4c-1.75 2.5-3.75 4.25-6 4.25S4.5 14.5 2.75 12Zm2.5 0h7M17 9.5l2.552 2.5L17 14.5M19.5 7a9 9 0 0 1 0 10");
}

</style>
