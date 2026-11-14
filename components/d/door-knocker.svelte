<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t4bkivbzy"/><path class="fi5a7guyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:door-knocker" {...props}></Icon>
<style>
:global(.fi5a7guyo) {
  d: path("M8 11.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.t4bkivbzy) {
  d: path("M5 2.5h14v19H5Zm7 3v2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
