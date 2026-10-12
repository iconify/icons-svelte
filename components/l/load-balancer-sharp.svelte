<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e9-7-8-2z"/><path class="sn3pd3b2c"/><circle class="fxwnb7vgp"/><circle class="zopjch_2q"/><circle class="xtsrmvj7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:load-balancer-sharp" {...props}></Icon>
<style>
:global(.e9-7-8-2z) {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

:global(.fxwnb7vgp) {
  cx: 5px;
  cy: 19px;
  r: 2px;
}

:global(.sn3pd3b2c) {
  d: path("M12 6.75V12m-7 5v-5h14v5m-7-5v5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xtsrmvj7o) {
  cx: 19px;
  cy: 19px;
  r: 2px;
}

:global(.zopjch_2q) {
  cx: 12px;
  cy: 19px;
  r: 2px;
}

</style>
