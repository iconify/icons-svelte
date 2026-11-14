<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0u3xslsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:limiting-reagent" {...props}></Icon>
<style>
:global(.r0u3xslsu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5L3 4v15a1.5 1.5 0 0 0 1.5 1.5h4A1.5 1.5 0 0 0 10 19V3.5m3.5 0l.5.5v15a1.5 1.5 0 0 0 1.5 1.5h4A1.5 1.5 0 0 0 21 19V3.5m-18 13h7m4-9h7");
}

</style>
