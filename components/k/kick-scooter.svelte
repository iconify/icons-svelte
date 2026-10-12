<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwi6umbbd"/><circle class="zwd9fjbht"/><circle class="nbxv73-5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kick-scooter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nbxv73-5j) {
  cx: 18.75px;
  cy: 18.5px;
  r: 2.25px;
}

:global(.pwi6umbbd) {
  d: path("M3.25 16.25h15m.08.04L16 4m-2.25 0h4.5");
}

:global(.zwd9fjbht) {
  cx: 5.25px;
  cy: 18.5px;
  r: 2.25px;
}

</style>
