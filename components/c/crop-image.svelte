<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eorzvx_sw"/><path class="hic28wblm"/><path class="wvmk1jbtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crop-image" {...props}></Icon>
<style>
:global(.eorzvx_sw) {
  d: path("M6.5 2.5v15h15");
}

:global(.hic28wblm) {
  d: path("M2.5 6.5h15v15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wvmk1jbtq) {
  d: path("M9.5 14.5L12 12l2.5 2.5m-.5-5h.01");
}

</style>
