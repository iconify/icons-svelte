<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m1qr1ab5l"/><path class="coet2kbql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bike-computer" {...props}></Icon>
<style>
:global(.coet2kbql) {
  d: path("M9 6h6v6H9Zm3 11v3.5m-9.5 0h19");
}

:global(.m1qr1ab5l) {
  d: path("M6 3h12v14H6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
