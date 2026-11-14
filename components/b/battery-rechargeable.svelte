<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ub29l-bqr"/><path class="mhxa_5fhj"/><path class="ytoduqagm"/><path class="fx2afhbrd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battery-rechargeable" {...props}></Icon>
<style>
:global(.fx2afhbrd) {
  d: path("m10.25 14.25l-1.75-1v2");
}

:global(.mhxa_5fhj) {
  d: path("M8.585 10.75a2.5 2.5 0 0 1 4.33 0");
}

:global(.ub29l-bqr) {
  d: path("M2.5 7H19v10H2.5Zm19 3.5v3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ytoduqagm) {
  d: path("m11.25 9.75l1.75 1v-2m-.085 4.5a2.5 2.5 0 0 1-4.33 0");
}

</style>
