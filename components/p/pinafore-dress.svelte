<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h34sj8bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pinafore-dress" {...props}></Icon>
<style>
:global(.h34sj8bjo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 7.5h7V12l4.5 9q-8 1.5-16 0l4.5-9Zm0 4.5h7m-7-4.5l-1-5m8 5l1-5");
}

</style>
