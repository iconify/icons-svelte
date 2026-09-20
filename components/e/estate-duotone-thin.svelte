<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ljm3e6bby"/><path class="z0s04-yke"/><path class="jtpiazbom"/><path class="lqyh0xxdq"/><path class="ws-a642hy"/><path class="jalxicbwq"/><path class="i2y9aacrj"/><path class="jllte9bnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:estate-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i2y9aacrj) {
  d: path("m12 12 5 -5 5 5");
}

:global(.jalxicbwq) {
  d: path("M3.5 12v8h7v-8");
}

:global(.jllte9bnc) {
  d: path("M13.5 12v8h7v-8");
}

:global(.jtpiazbom) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 12 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ljm3e6bby) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 12 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lqyh0xxdq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 12v8h7v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ws-a642hy) {
  d: path("m2 12 5 -5 5 5");
}

:global(.z0s04-yke) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3.5 12v8h7v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
