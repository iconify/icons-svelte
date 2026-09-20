<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qw2xzud5v"/><path class="zkzt1gb8v"/><path class="aw7ppbc1j"/><path class="zww0vqboc"/><path class="bc7uaebvz"/><path class="b5rbpxbdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:external-link-duotone-bold" {...props}></Icon>
<style>
:global(.aw7ppbc1j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 4h6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b5rbpxbdb) {
  d: path("M14 4h6v6");
}

:global(.bc7uaebvz) {
  d: path("m12 12 8 -8");
}

:global(.qw2xzud5v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 6H4v14h14v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zkzt1gb8v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 12 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zww0vqboc) {
  d: path("M10 6H4v14h14v-6");
}

</style>
