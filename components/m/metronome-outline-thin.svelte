<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wgokw4bbc"/><path class="oifr9zbpt"/><path class="x5li7lwaz"/><path class="oio7uh0en"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metronome-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.oio7uh0en) {
  d: path("M10 11h4");
}

:global(.wgokw4bbc) {
  d: path("M4 20c1 -7 4 -14 6 -17h4c2 3 5 10 6 17");
}

:global(.x5li7lwaz) {
  d: path("M12 7v12");
}

</style>
