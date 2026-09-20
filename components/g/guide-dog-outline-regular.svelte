<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="avtblzbgk"/><path class="nie_edcrf"/><path class="midjlmbqm"/><path class="krhtkbcno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:guide-dog-outline-regular" {...props}></Icon>
<style>
:global(.avtblzbgk) {
  d: path("M6 20v-7h10v7");
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

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
