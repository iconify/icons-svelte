<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xwgs6ybpy"/><path class="rsqbw-b4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:room-add" {...props}></Icon>
<style>
:global(.rsqbw-b4i) {
  d: path("M5 19a5 5 0 0 1 5-5m8 1v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xwgs6ybpy) {
  d: path("M10 19h2.2m6.8-6.8V2.5H2.5V19H5m5 0v-5");
}

</style>
