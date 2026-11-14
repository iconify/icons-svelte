<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9wdz6b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:penalty-card" {...props}></Icon>
<style>
:global(.b9wdz6b3j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.273 3.135l9.781 2.079l-3.327 15.651l-9.781-2.079ZM18.5 7.5l3-1.5M19 12h2.5");
}

</style>
