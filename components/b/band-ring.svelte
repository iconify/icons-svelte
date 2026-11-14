<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ywild8b0o"/><path class="crt2xgbyp"/><path class="t9r0xhbbf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:band-ring" {...props}></Icon>
<style>
:global(.crt2xgbyp) {
  d: path("M3 10.25v3.25a9 5.25 0 0 0 18 0v-3.25");
}

:global(.t9r0xhbbf) {
  d: path("M6 10.25a6 2 0 1 0 12 0a6 2 0 1 0-12 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ywild8b0o) {
  d: path("M3 10.25a9 5.25 0 1 0 18 0a9 5.25 0 1 0-18 0Z");
}

</style>
