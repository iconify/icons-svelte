<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8abqfbpc"/><path class="h_c4fk0bb"/><path class="l3hfq7bhw"/><path class="gjmq94baq"/><path class="lfyekl_xx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:map-scale-outline-regular" {...props}></Icon>
<style>
:global(.d8abqfbpc) {
  d: path("M3 11h18");
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

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
