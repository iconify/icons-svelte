<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="it2yb1hje"/><path class="jdcw1mb1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:block" {...props}></Icon>
<style>
:global(.it2yb1hje) {
  d: path("m12 2.5l8.5 5v9l-8.5 5l-8.5-5v-9Z");
}

:global(.jdcw1mb1z) {
  d: path("m3.5 7.5l8.5 5l8.5-5m-8.5 5v9M7.75 5l8.5 5m0-5l-8.5 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
