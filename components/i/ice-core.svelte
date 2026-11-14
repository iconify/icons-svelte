<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mgbc3-bkm"/><path class="ym9vz_bku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ice-core" {...props}></Icon>
<style>
:global(.mgbc3-bkm) {
  d: path("M8 4.5a4 1.5 0 1 0 8 0a4 1.5 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ym9vz_bku) {
  d: path("M8 4.5v15a4 1.5 0 0 0 8 0v-15m-8 6L16 9m-8 7l8-2");
}

</style>
