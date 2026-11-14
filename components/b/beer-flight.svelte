<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf-03pabp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:beer-flight" {...props}></Icon>
<style>
:global(.mf-03pabp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h19v3h-19Zm1.25-8.5H7.5L7 15H4.25Zm6.5 0H14l-.5 8.5h-2.75Zm6.5 0h3.75L20 15h-2.75Z");
}

</style>
