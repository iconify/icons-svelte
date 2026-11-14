<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zcr9vvbxo"/><path class="c7rk0uhzz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:generator-event" {...props}></Icon>
<style>
:global(.c7rk0uhzz) {
  d: path("M10.5 10.75L7.75 14.5H11l-2.75 3.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zcr9vvbxo) {
  d: path("M2.5 8H16v12.5H2.5Zm3 0V4.5h5V8M13 8V3.5h2.5M16 14h2.5c1 0 1.75.75 1.75 2v1m-1.5 0h2.75v3h-2.75Z");
}

</style>
