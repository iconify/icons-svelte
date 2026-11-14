<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zn9l-eawd"/><path class="j1hnyjv5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rocket-x" {...props}></Icon>
<style>
:global(.j1hnyjv5o) {
  d: path("M6 11.5L3 15v3l3-2m6-4.5l1.6 1.921M9 18.75v2.75m6.5-6l5 5m0-5l-5 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zn9l-eawd) {
  d: path("M11.991 16H6C5 10 5.5 5 9 2.5c3.285 2.346 3.927 6.895 3.167 12.406");
}

</style>
