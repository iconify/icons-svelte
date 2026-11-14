<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cixusfbwk"/><path class="to_vcqswz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:butcher-shop" {...props}></Icon>
<style>
:global(.cixusfbwk) {
  d: path("M5 2.5h14v11H5Zm9.5 11v6.25a1.75 1.75 0 0 0 3.5 0V13.5");
}

:global(.to_vcqswz) {
  d: path("M7 6.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
