<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rm1tb6aya"/><path class="mk93lqrnh"/><path class="scp1py_mj"/><path class="yzvng5w1c"/><path class="rpjwsjb7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:disability-outline-regular" {...props}></Icon>
<style>
:global(.mk93lqrnh) {
  d: path("M7 8v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rm1tb6aya) {
  d: path("M4 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.rpjwsjb7m) {
  d: path("M16 11h5");
}

:global(.scp1py_mj) {
  d: path("m2 19 5 -5 5 5");
}

:global(.yzvng5w1c) {
  d: path("M16 7v13");
}

</style>
