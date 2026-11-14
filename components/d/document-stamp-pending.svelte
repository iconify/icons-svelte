<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pjkttgd5g"/><path class="sbezkcbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:document-stamp-pending" {...props}></Icon>
<style>
:global(.pjkttgd5g) {
  d: path("M8.5 11.5V9.75C8.5 8.75 7.25 8 7.25 6a3.25 3.25 0 0 1 6.5 0c0 2-1.25 2.75-1.25 3.75v1.75m.2 4.5H3v-4.5h15v.4M4.5 19.5h8.2m2.8-4.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

:global(.sbezkcbzn) {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
