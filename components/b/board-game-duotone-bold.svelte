<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p28r88boo"/><path class="nizbrguot"/><path class="k8y9e5sub"/><path class="bslg5pcgg"/><path class="ae-e09b3w"/><path class="of_dlbc-j"/><path class="mkaclw6aw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:board-game-duotone-bold" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.bslg5pcgg) {
  d: path("M3 6v12h18V6Z");
}

:global(.k8y9e5sub) {
  fill: currentColor;
  d: path("M14 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mkaclw6aw) {
  d: path("M14 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nizbrguot) {
  fill: currentColor;
  d: path("M6 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.of_dlbc-j) {
  d: path("M6 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.p28r88boo) {
  fill: currentColor;
  d: path("M3 6v12h18V6Z");
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

</style>
