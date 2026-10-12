<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="qcz3cfb1g"/><path class="wcpvigl8r"/><path class="sdxbftj8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:alarm-siren-sharp" {...props}></Icon>
<style>
:global(.qcz3cfb1g) {
  cx: 12px;
  cy: 10px;
  r: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sdxbftj8d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14.25v3m-3.25 0h6.5v4h-6.5zm-2.28-3.38a6.75 6.75 0 0 1 0-7.74m-2.05 9.18a9.25 9.25 0 0 1 0-10.62m13.11 1.44a6.75 6.75 0 0 1 0 7.74m2.05-9.18a9.25 9.25 0 0 1 0 10.62");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wcpvigl8r) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10h.01");
}

</style>
