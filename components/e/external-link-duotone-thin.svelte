<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rgqkl84gj"/><path class="bf3tjvl-t"/><path class="lars80xge"/><path class="zww0vqboc"/><path class="bc7uaebvz"/><path class="b5rbpxbdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:external-link-duotone-thin" {...props}></Icon>
<style>
:global(.b5rbpxbdb) {
  d: path("M14 4h6v6");
}

:global(.bc7uaebvz) {
  d: path("m12 12 8 -8");
}

:global(.bf3tjvl-t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 12 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lars80xge) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 4h6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rgqkl84gj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 6H4v14h14v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zww0vqboc) {
  d: path("M10 6H4v14h14v-6");
}

</style>
