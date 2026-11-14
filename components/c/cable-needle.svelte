<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kvo74gbmt"/><path class="ocaez4f_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cable-needle" {...props}></Icon>
<style>
:global(.kvo74gbmt) {
  d: path("M7 3v13a4.5 4.5 0 0 0 9 0v-6");
}

:global(.ocaez4f_f) {
  d: path("M4 9.5c0-3.5 6-3.5 6 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
