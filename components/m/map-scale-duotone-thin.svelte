<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yf_brbf0s"/><path class="srrwlob2l"/><path class="vnzngacab"/><path class="cpiyi4b5g"/><path class="fkewqabpv"/><path class="d8abqfbpc"/><path class="h_c4fk0bb"/><path class="l3hfq7bhw"/><path class="gjmq94baq"/><path class="lfyekl_xx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:map-scale-duotone-thin" {...props}></Icon>
<style>
:global(.cpiyi4b5g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.fkewqabpv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gjmq94baq) {
  d: path("M15 11v4");
}

:global(.h_c4fk0bb) {
  d: path("M3 11v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l3hfq7bhw) {
  d: path("M9 11v4");
}

:global(.lfyekl_xx) {
  d: path("M21 11v6");
}

:global(.srrwlob2l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vnzngacab) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yf_brbf0s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
