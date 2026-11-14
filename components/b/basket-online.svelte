<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iau37ab1m"/><path class="l08wfcb_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:basket-online" {...props}></Icon>
<style>
:global(.iau37ab1m) {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8");
}

:global(.l08wfcb_y) {
  d: path("M7.75 9.25h8.5l-1 4h-6.5Zm1.75 0a2.5 2.5 0 0 1 5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
