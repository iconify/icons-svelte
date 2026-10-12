<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zk_z2zbfs"/><circle class="f27_oi5kf"/><path class="up99124la"/><path class="vgktj9bsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:price-tag-percent-sharp" {...props}></Icon>
<style>
:global(.f27_oi5kf) {
  cx: 12px;
  cy: 7.75px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.up99124la) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.75 17.5l4.5-4.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vgktj9bsy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 13h.01m4.49 4.5h.01");
}

:global(.zk_z2zbfs) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.85 6.6l4.4-3.6l.75-.6l.75.6l4.4 3.6l.601.589l-.001.841v13.22H6.25V8.03l-.001-.841z");
}

</style>
