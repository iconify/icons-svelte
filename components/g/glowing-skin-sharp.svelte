<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jg7xt1_6k"/><path class="j28rvfb_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:glowing-skin-sharp" {...props}></Icon>
<style>
:global(.j28rvfb_n) {
  d: path("m6.75 13l1 1.182l1-1.182m2.5 0l1 1.182l1-1.182M8.5 16.75l1.5 1.125l1.5-1.125m6.5-14l.542 2.708L21.25 6l-2.708.542L18 9.25l-.542-2.708L14.75 6l2.708-.542z");
}

:global(.jg7xt1_6k) {
  cx: 10px;
  cy: 14px;
  r: 7.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
