<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvwwsc7zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:golf-trolley" {...props}></Icon>
<style>
:global(.zvwwsc7zg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7h7v13h-7Zm7 2.5l5-5.5m-5 14h4m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7 7V3.5H5M9.5 7V2.5h2");
}

</style>
