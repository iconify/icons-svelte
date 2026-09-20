<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nhri7pb9i"/><path class="gsl5knvuq"/><path class="xa52mrrsy"/><path class="e5d_yrbyo"/><path class="z82iob5ig"/><path class="q9naw_b2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mist-outline-regular" {...props}></Icon>
<style>
:global(.e5d_yrbyo) {
  d: path("M12 13h9");
}

:global(.gsl5knvuq) {
  d: path("M15 8h6");
}

:global(.nhri7pb9i) {
  d: path("M3 8h9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q9naw_b2m) {
  d: path("M17 18h4");
}

:global(.xa52mrrsy) {
  d: path("M3 13h6");
}

:global(.z82iob5ig) {
  d: path("M5 18h9");
}

</style>
