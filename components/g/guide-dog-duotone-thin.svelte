<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zi2vgzezl"/><path class="lfyxabcmu"/><path class="w9vap4dng"/><path class="bv0s6abdo"/><path class="avtblzbgk"/><path class="nie_edcrf"/><path class="midjlmbqm"/><path class="krhtkbcno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guide-dog-duotone-thin" {...props}></Icon>
<style>
:global(.avtblzbgk) {
  d: path("M6 20v-7h10v7");
}

:global(.bv0s6abdo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 13 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.krhtkbcno) {
  d: path("m6 13 -3 -3");
}

:global(.lfyxabcmu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 13V7h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.midjlmbqm) {
  d: path("m16 7 -3 -3");
}

:global(.nie_edcrf) {
  d: path("M16 13V7h5v4");
}

:global(.w9vap4dng) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 7 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zi2vgzezl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20v-7h10v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
