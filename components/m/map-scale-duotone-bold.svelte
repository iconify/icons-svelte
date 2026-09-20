<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g55pkgb9q"/><path class="bzmzml3bu"/><path class="riogcmb0z"/><path class="db4nonbww"/><path class="ud-xiac5d"/><path class="d8abqfbpc"/><path class="h_c4fk0bb"/><path class="l3hfq7bhw"/><path class="gjmq94baq"/><path class="lfyekl_xx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:map-scale-duotone-bold" {...props}></Icon>
<style>
:global(.bzmzml3bu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.db4nonbww) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g55pkgb9q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gjmq94baq) {
  d: path("M15 11v4");
}

:global(.h_c4fk0bb) {
  d: path("M3 11v6");
}

:global(.l3hfq7bhw) {
  d: path("M9 11v4");
}

:global(.lfyekl_xx) {
  d: path("M21 11v6");
}

:global(.riogcmb0z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ud-xiac5d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
