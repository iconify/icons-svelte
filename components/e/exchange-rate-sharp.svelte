<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="qtr58-ckh"/><circle class="azpvbcbbw"/><path class="uscb7h6rg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:exchange-rate-sharp" {...props}></Icon>
<style>
:global(.azpvbcbbw) {
  cx: 16.5px;
  cy: 16.5px;
  r: 4.5px;
}

:global(.qtr58-ckh) {
  cx: 7.5px;
  cy: 7.5px;
  r: 4.5px;
}

:global(.uscb7h6rg) {
  d: path("M14.5 4.5H19v5.25m-2-2l2 2l2-2M9.5 19.5H5v-5.25m2 2l-2-2l-2 2");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
