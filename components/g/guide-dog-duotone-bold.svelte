<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rkcew_bzu"/><path class="b00xxu-nn"/><path class="npyvz1bww"/><path class="df8exkb3c"/><path class="avtblzbgk"/><path class="nie_edcrf"/><path class="midjlmbqm"/><path class="krhtkbcno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guide-dog-duotone-bold" {...props}></Icon>
<style>
:global(.avtblzbgk) {
  d: path("M6 20v-7h10v7");
}

:global(.b00xxu-nn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 13V7h5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.df8exkb3c) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 13 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.krhtkbcno) {
  d: path("m6 13 -3 -3");
}

:global(.midjlmbqm) {
  d: path("m16 7 -3 -3");
}

:global(.nie_edcrf) {
  d: path("M16 13V7h5v4");
}

:global(.npyvz1bww) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 7 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkcew_bzu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 20v-7h10v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
