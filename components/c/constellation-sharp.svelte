<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qchdveb1r"/><circle class="zpsdcem0w"/><circle class="l-zqvscmh"/><circle class="fpa2g8b6y"/><circle class="irgw4ubmp"/><path class="pi-tiw66b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:constellation-sharp" {...props}></Icon>
<style>
:global(.fpa2g8b6y) {
  cx: 14px;
  cy: 13.5px;
  r: 1.25px;
}

:global(.irgw4ubmp) {
  cx: 19px;
  cy: 19px;
  r: 1.25px;
}

:global(.l-zqvscmh) {
  cx: 7.5px;
  cy: 11px;
  r: 1.25px;
}

:global(.pi-tiw66b) {
  d: path("m18.5 2.75l.33 2.42l2.42.33l-2.42.33l-.33 2.42l-.33-2.42l-2.42-.33l2.42-.33z");
}

:global(.qchdveb1r) {
  d: path("m5.29 16.89l1.42-3.78m2.89-1.3l2.3.88m3.2-1.15l1.68-2.99m-1.27 6.61l1.98 2.18");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zpsdcem0w) {
  cx: 4.5px;
  cy: 19px;
  r: 1.25px;
}

</style>
