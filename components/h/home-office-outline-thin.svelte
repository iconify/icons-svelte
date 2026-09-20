<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m2rbp207a"/><path class="rrzohjbez"/><path class="l8dn9jbyp"/><path class="yfv778qvg"/><path class="bg9lr2bcw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-office-outline-thin" {...props}></Icon>
<style>
:global(.bg9lr2bcw) {
  d: path("M20 15v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.m2rbp207a) {
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.rrzohjbez) {
  d: path("M12 12v3");
}

:global(.yfv778qvg) {
  d: path("M4 15v6");
}

</style>
