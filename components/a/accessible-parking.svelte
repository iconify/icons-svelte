<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dkag5ac0u"/><path class="yu1r-pdvb"/><path class="f1bbb0bma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:accessible-parking" {...props}></Icon>
<style>
:global(.dkag5ac0u) {
  d: path("M3 3h18v18H3Zm8 4h.01");
}

:global(.f1bbb0bma) {
  d: path("M10.5 11.25a3.5 3.5 0 1 1-3.5 3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yu1r-pdvb) {
  d: path("M11 9.75v4.5h3.75l1.75 3.5");
}

</style>
