<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6btd475d"/><path class="bkuclybie"/><path class="nuhfel7ej"/><path class="eqpdiibxq"/><path class="ja7s-m1mr"/><path class="ygcr2n8so"/><path class="mn-a1zb6m"/><path class="e2kgfl2ea"/><path class="s25-orfog"/><path class="jv3d31_7h"/><path class="x1_r36phd"/><path class="jkjmjem6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:follow-back-duotone-thin" {...props}></Icon>
<style>
:global(.bkuclybie) {
  fill: currentColor;
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e2kgfl2ea) {
  d: path("M2 15a3 3 0 0 1 6 0");
}

:global(.eqpdiibxq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g6btd475d) {
  fill: currentColor;
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja7s-m1mr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkjmjem6y) {
  d: path("m11 10 -2 2 2 2");
}

:global(.jv3d31_7h) {
  d: path("M16 15a3 3 0 0 1 6 0");
}

:global(.mn-a1zb6m) {
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nuhfel7ej) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s25-orfog) {
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.ygcr2n8so) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 10 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
