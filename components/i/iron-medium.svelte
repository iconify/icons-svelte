<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="acea_dbyh"/><path class="p130bubnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:iron-medium" {...props}></Icon>
<style>
:global(.acea_dbyh) {
  d: path("M3 18c.5-4 4-6.5 8.5-6.5H21V18Zm7.5-6.5l1.5-5h7.5v5");
}

:global(.p130bubnq) {
  fill: currentColor;
  d: path("M11.75 15a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm4 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
