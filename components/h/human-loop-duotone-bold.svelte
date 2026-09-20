<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tbr--mb3k"/><path class="wz2u9fjma"/><path class="fjjtwtbze"/><path class="s6ftf884l"/><path class="pjcnnqbic"/><path class="u52vfsbff"/><path class="xedmbxbzm"/><path class="jkqgno60a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:human-loop-duotone-bold" {...props}></Icon>
<style>
:global(.fjjtwtbze) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkqgno60a) {
  d: path("M8.5 17a3.5 3.5 0 0 1 7 0");
}

:global(.pjcnnqbic) {
  d: path("M16 5.07a8 8 0 1 1 -8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s6ftf884l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.5 17a3.5 3.5 0 0 1 7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tbr--mb3k) {
  fill: currentColor;
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u52vfsbff) {
  d: path("M5 4h3v3");
}

:global(.wz2u9fjma) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 5.07a8 8 0 1 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xedmbxbzm) {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
