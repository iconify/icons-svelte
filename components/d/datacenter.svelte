<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq37bjbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:datacenter" {...props}></Icon>
<style>
:global(.oq37bjbry) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h8v19h-8Zm11 0h8v19h-8ZM5.25 7h2.5m-2.5 4h2.5m8.5-4h2.5m-2.5 4h2.5");
}

</style>
