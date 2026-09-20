<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xx19s5bxb"/><path class="bwarilbuc"/><path class="q5jw2tb7h"/><path class="j2ded1bub"/><path class="beaxg8pyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-cooking-duotone-bold" {...props}></Icon>
<style>
:global(.beaxg8pyo) {
  d: path("M13 9c2 -2 0 -4 2 -6");
}

:global(.bwarilbuc) {
  d: path("M3 12h14c0 5 -3 8 -7 8s-7 -3 -7 -8");
}

:global(.j2ded1bub) {
  d: path("M8 9c2 -2 0 -4 2 -6");
}

:global(.q5jw2tb7h) {
  d: path("m17 12 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xx19s5bxb) {
  fill: currentColor;
  d: path("M3 12h14c0 5 -3 8 -7 8s-7 -3 -7 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
