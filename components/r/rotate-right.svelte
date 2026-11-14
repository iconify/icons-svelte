<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6wn4v-tc"/><path class="lvnpwkv_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rotate-right" {...props}></Icon>
<style>
:global(.g6wn4v-tc) {
  d: path("M3.5 20A13.5 13.5 0 0 1 17 6.5");
}

:global(.lvnpwkv_c) {
  d: path("M13.5 3L17 6.5L13.5 10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
