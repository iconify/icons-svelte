<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gc9bpdn0n"/><path class="goa6xmsjx"/><circle class="evze8sb2n"/><path class="jsqqbh54i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:effects-pedal-sharp" {...props}></Icon>
<style>
:global(.evze8sb2n) {
  cx: 12px;
  cy: 16.25px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.gc9bpdn0n) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 6.75h14.5v14.5H4.75z");
}

:global(.goa6xmsjx) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01");
}

:global(.jsqqbh54i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.75v-4m7 4v-4");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
