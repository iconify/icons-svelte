<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wwkc4-bza"/><path class="dld4-db-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:driver-license-check" {...props}></Icon>
<style>
:global(.dld4-db-m) {
  d: path("M6.25 8.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM5 15.5a3 3 0 0 1 6 0M13.5 9H18m-3.25 9l2 2L21 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wwkc4-bza) {
  d: path("M11.3 18.5H2.5v-15h19v8.8");
}

</style>
