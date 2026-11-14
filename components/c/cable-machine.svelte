<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nohtw3bix"/><path class="cgbh1is6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cable-machine" {...props}></Icon>
<style>
:global(.cgbh1is6m) {
  d: path("M13 6a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM2.5 21.5h7M18 6v9.5m-3.5 0h7");
}

:global(.nohtw3bix) {
  d: path("M5 21.5v-18h10.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
