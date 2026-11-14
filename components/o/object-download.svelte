<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kchzq-b0q"/><path class="r43531bri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:object-download" {...props}></Icon>
<style>
:global(.kchzq-b0q) {
  d: path("m12 10.5l6.5 3.25v5L12 22l-6.5-3.25v-5Z");
}

:global(.r43531bri) {
  d: path("M5.5 13.75L12 17l6.5-3.25M12 17v5m0-20v5.75m-2.5-2.5l2.5 2.5l2.5-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
