<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p-kewib7t"/><path class="wlpoxdi9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:air-bike" {...props}></Icon>
<style>
:global(.p-kewib7t) {
  d: path("M3 11a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm16.25-7v16.5M16.75 4h4.75M3 20.5h18.5M16 11h3.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wlpoxdi9i) {
  d: path("M9.5 11a3.25 3.25 0 0 1 0-6.5m0 6.5a3.25 3.25 0 0 1 6.5 0m-6.5 0a3.25 3.25 0 0 1 0 6.5m0-6.5A3.25 3.25 0 0 1 3 11");
}

</style>
