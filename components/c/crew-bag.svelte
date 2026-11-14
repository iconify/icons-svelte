<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b_wni_bvj"/><path class="dt3udrbcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crew-bag" {...props}></Icon>
<style>
:global(.b_wni_bvj) {
  d: path("M4 9.5h16a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1Zm6 0v-1A1.5 1.5 0 0 1 11.5 7h1A1.5 1.5 0 0 1 14 8.5v1");
}

:global(.dt3udrbcs) {
  d: path("M6.5 9.5c0-8 11-8 11 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
