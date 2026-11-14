<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msvln8b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coat-hooks" {...props}></Icon>
<style>
:global(.msvln8b-t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h19V10h-19Zm2 3.5v6.5a1.5 1.5 0 0 0 3 0v-1m3-5.5v6.5a1.5 1.5 0 0 0 3 0v-1m3-5.5v6.5a1.5 1.5 0 0 0 3 0v-1");
}

</style>
