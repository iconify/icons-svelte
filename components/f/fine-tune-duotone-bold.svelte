<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="edllzuogn"/><path class="p33184bqk"/><path class="m1o3_obxt"/><path class="iaozfqbuj"/><path class="l0zc9ibud"/><path class="kr1cz4b8j"/><path class="mvm7r4bea"/><path class="xaev2ybax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fine-tune-duotone-bold" {...props}></Icon>
<style>
:global(.edllzuogn) {
  fill: currentColor;
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iaozfqbuj) {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

:global(.kr1cz4b8j) {
  d: path("M9 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.l0zc9ibud) {
  d: path("M8 10h8");
}

:global(.m1o3_obxt) {
  fill: currentColor;
  d: path("M13 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mvm7r4bea) {
  d: path("M8 14h8");
}

:global(.p33184bqk) {
  fill: currentColor;
  d: path("M9 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xaev2ybax) {
  d: path("M13 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
