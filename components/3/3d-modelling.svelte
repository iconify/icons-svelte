<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iau37ab1m"/><path class="enjznc75v"/><path class="v_hslublf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:3d-modelling" {...props}></Icon>
<style>
:global(.enjznc75v) {
  d: path("m12 6.25l3.25 2v3.5l-3.25 2l-3.25-2v-3.5Z");
}

:global(.iau37ab1m) {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v_hslublf) {
  d: path("m8.75 8.25l3.25 2l3.25-2m-3.25 2v3.5");
}

</style>
