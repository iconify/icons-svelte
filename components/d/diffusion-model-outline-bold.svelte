<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iaozfqbuj"/><path class="c4o3x9bhp"/><path class="chgl46v6k"/><path class="i3rtqmu1v"/><path class="vny6l674c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diffusion-model-outline-bold" {...props}></Icon>
<style>
:global(.c4o3x9bhp) {
  d: path("M8 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.chgl46v6k) {
  d: path("M13.5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.i3rtqmu1v) {
  d: path("M9 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.iaozfqbuj) {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vny6l674c) {
  d: path("M14.5 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
