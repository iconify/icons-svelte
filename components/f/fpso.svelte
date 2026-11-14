<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z532i3bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fpso" {...props}></Icon>
<style>
:global(.z532i3bjc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19l-2 4h-15Zm2 0V9.25a2.25 2.25 0 0 1 4.5 0V12m2.75 0V9.25a2.25 2.25 0 0 1 4.5 0V12M19 12V4.5M2.5 20q2.25-2.25 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
