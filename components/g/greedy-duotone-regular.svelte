<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="elo9fvbju"/><path class="t1ic5ob8h"/><path class="g2z_jkb5q"/><path class="zxc3qhbmd"/><path class="zwghjjvbs"/><path class="azskw1rof"/><path class="fbyngunlt"/><path class="bie4u9bix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:greedy-duotone-regular" {...props}></Icon>
<style>
:global(.azskw1rof) {
  d: path("m9 16 5 -5");
}

:global(.bie4u9bix) {
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.elo9fvbju) {
  fill: currentColor;
  d: path("M14 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fbyngunlt) {
  d: path("M14 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.g2z_jkb5q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t1ic5ob8h) {
  fill: currentColor;
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zwghjjvbs) {
  d: path("M2 16h7");
}

:global(.zxc3qhbmd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
