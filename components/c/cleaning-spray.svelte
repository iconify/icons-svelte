<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z83516bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cleaning-spray" {...props}></Icon>
<style>
:global(.z83516bha) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8.5V3h7l2.5 2.5H12v3Zm0 0L4.5 12v8A1.5 1.5 0 0 0 6 21.5h8a1.5 1.5 0 0 0 1.5-1.5v-8L12 8.5Zm12.5-5.75h.01m.74 2.75h.01m-.76 2.75h.01");
}

</style>
