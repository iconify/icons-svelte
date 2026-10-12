<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ox05rfewb"/><path class="lqs531bhw"/><path class="w_8vmacqn"/><path class="y8-9lwbtm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:power-supply-sharp" {...props}></Icon>
<style>
:global(.lqs531bhw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 7.75a4.25 4.25 0 1 1 0 8.5a4.25 4.25 0 1 1 0-8.5");
}

:global(.ox05rfewb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.w_8vmacqn) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12h.01");
}

:global(.y8-9lwbtm) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 8h2.5v4H16zm0 7.75h2.5");
}

</style>
