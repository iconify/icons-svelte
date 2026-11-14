<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl03xkb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:active-active" {...props}></Icon>
<style>
:global(.tl03xkb7j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h8v16h-8Zm11 0h8v16h-8Zm-3 8h3M5.25 8h2.5m8.5 0h2.5M6.5 15.5h.01m10.99 0h.01");
}

</style>
