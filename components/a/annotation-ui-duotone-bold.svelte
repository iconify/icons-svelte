<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aidevdbbz"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="fo31dvbxr"/><path class="wmg5scbww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:annotation-ui-duotone-bold" {...props}></Icon>
<style>
:global(.aidevdbbz) {
  fill: currentColor;
  d: path("M3 14h7l3 3 -3 3H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fo31dvbxr) {
  d: path("M3 14h7l3 3 -3 3H3Z");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wmg5scbww) {
  d: path("M17 14v6");
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

</style>
