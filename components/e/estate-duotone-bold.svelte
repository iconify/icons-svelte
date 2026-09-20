<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e-7eylbmz"/><path class="j7q0iebzu"/><path class="ugjxj4v5w"/><path class="re8yolbvl"/><path class="ws-a642hy"/><path class="jalxicbwq"/><path class="i2y9aacrj"/><path class="jllte9bnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:estate-duotone-bold" {...props}></Icon>
<style>
:global(.e-7eylbmz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m2 12 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i2y9aacrj) {
  d: path("m12 12 5 -5 5 5");
}

:global(.j7q0iebzu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3.5 12v8h7v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jalxicbwq) {
  d: path("M3.5 12v8h7v-8");
}

:global(.jllte9bnc) {
  d: path("M13.5 12v8h7v-8");
}

:global(.re8yolbvl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.5 12v8h7v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ugjxj4v5w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 12 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ws-a642hy) {
  d: path("m2 12 5 -5 5 5");
}

</style>
