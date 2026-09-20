<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zww0vqboc"/><path class="bc7uaebvz"/><path class="b5rbpxbdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:external-link-outline-regular" {...props}></Icon>
<style>
:global(.b5rbpxbdb) {
  d: path("M14 4h6v6");
}

:global(.bc7uaebvz) {
  d: path("m12 12 8 -8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zww0vqboc) {
  d: path("M10 6H4v14h14v-6");
}

</style>
