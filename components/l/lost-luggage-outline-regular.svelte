<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="duisldofr"/><path class="zmc7aqkcp"/><path class="rrzohjbez"/><path class="jlojnsdlu"/><path class="sts7iebwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lost-luggage-outline-regular" {...props}></Icon>
<style>
:global(.duisldofr) {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.jlojnsdlu) {
  d: path("M11 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rrzohjbez) {
  d: path("M12 12v3");
}

:global(.sts7iebwd) {
  d: path("M9.5 10.5a2.5 2.5 0 0 1 5 0");
}

:global(.zmc7aqkcp) {
  d: path("M9 6V3h6v3");
}

</style>
