<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ws-a642hy"/><path class="jalxicbwq"/><path class="i2y9aacrj"/><path class="jllte9bnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:estate-outline-regular" {...props}></Icon>
<style>
:global(.i2y9aacrj) {
  d: path("m12 12 5 -5 5 5");
}

:global(.jalxicbwq) {
  d: path("M3.5 12v8h7v-8");
}

:global(.jllte9bnc) {
  d: path("M13.5 12v8h7v-8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ws-a642hy) {
  d: path("m2 12 5 -5 5 5");
}

</style>
