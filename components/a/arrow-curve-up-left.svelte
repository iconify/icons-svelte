<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uhir2-m7c"/><path class="usxb4tbdz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-curve-up-left" {...props}></Icon>
<style>
:global(.uhir2-m7c) {
  d: path("M16 21v-7c0-2-.75-3.75-2-5L8 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.usxb4tbdz) {
  d: path("M13 3H8v5");
}

</style>
