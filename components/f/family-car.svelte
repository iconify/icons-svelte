<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y2uknf45d"/><circle class="rqad3rgfm"/><circle class="ay165rc5y"/><path class="mpb8zwbqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:family-car" {...props}></Icon>
<style>
:global(.ay165rc5y) {
  cx: 17px;
  cy: 19.25px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mpb8zwbqv) {
  d: path("m12 12.75l-1.6-1.55A1.05 1.05 0 0 1 12 9.85a1.05 1.05 0 0 1 1.6 1.35Z");
}

:global(.rqad3rgfm) {
  cx: 7px;
  cy: 19.25px;
  r: 1.75px;
}

:global(.y2uknf45d) {
  d: path("M2.75 14v-2.6A2 2 0 0 1 4.3 9.45l2.45-.55L8.8 5.45a2 2 0 0 1 1.72-.95h2.96a2 2 0 0 1 1.72.95l2.05 3.45l2.45.55a2 2 0 0 1 1.55 1.95V14a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1");
}

</style>
