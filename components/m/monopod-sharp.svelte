<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l4n1lkbke"/><circle class="r8335-baj"/><path class="fq8fayugl"/><path class="rcbqokfet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monopod-sharp" {...props}></Icon>
<style>
:global(.fq8fayugl) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 5.25h.01");
}

:global(.l4n1lkbke) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h14.5v9H4.75z");
}

:global(.r8335-baj) {
  cx: 12px;
  cy: 7.25px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rcbqokfet) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.75v7.75m-3 1.75l3-1.75l3 1.75");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
