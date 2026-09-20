<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dhi9jdbkg"/><path class="jiw8u-asa"/><path class="ujz4z0bsw"/><path class="r-6mxobrl"/><path class="wgokw4bbc"/><path class="oifr9zbpt"/><path class="x5li7lwaz"/><path class="oio7uh0en"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metronome-duotone-bold" {...props}></Icon>
<style>
:global(.dhi9jdbkg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20c1 -7 4 -14 6 -17h4c2 3 5 10 6 17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.oio7uh0en) {
  d: path("M10 11h4");
}

:global(.r-6mxobrl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ujz4z0bsw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wgokw4bbc) {
  d: path("M4 20c1 -7 4 -14 6 -17h4c2 3 5 10 6 17");
}

:global(.x5li7lwaz) {
  d: path("M12 7v12");
}

</style>
