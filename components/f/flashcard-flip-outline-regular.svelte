<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q1wra3bex"/><path class="zlf0p6b7k"/><path class="qj71t0baf"/><path class="t_rr8ablw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flashcard-flip-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q1wra3bex) {
  d: path("M2 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.qj71t0baf) {
  d: path("M4 19h8");
}

:global(.t_rr8ablw) {
  d: path("m7 16 -3 3 3 3");
}

:global(.zlf0p6b7k) {
  d: path("M8 9a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H10a2 2 0 0 1 -2 -2Z");
}

</style>
