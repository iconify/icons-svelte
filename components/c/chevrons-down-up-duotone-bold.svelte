<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="obc-z3jlg"/><path class="iv2c1_7mk"/><path class="p8a7rmkzk"/><path class="eev_c9mlp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-down-up-duotone-bold" {...props}></Icon>
<style>
:global(.eev_c9mlp) {
  d: path("m7 20 5 -5 5 5");
}

:global(.iv2c1_7mk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 20 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.obc-z3jlg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 4 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p8a7rmkzk) {
  d: path("m7 4 5 5 5 -5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
