<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ws-a642hy"/><path class="jalxicbwq"/><path class="i2y9aacrj"/><path class="jllte9bnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:estate-outline-bold" {...props}></Icon>
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

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ws-a642hy) {
  d: path("m2 12 5 -5 5 5");
}

</style>
