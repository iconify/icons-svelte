<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fxfo558wv"/><path class="t2kmfuk0y"/><path class="lb65jobfp"/><path class="pw61xnbei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pram-outline-thin" {...props}></Icon>
<style>
:global(.fxfo558wv) {
  d: path("M4 13a8 8 0 0 1 16 0Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lb65jobfp) {
  d: path("M7 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.pw61xnbei) {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.t2kmfuk0y) {
  d: path("m4 13 4 4h12v-4");
}

</style>
