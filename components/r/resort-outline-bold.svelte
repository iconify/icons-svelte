<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k4wc6x-hq"/><path class="n_xjdobth"/><path class="ghuq2xb5p"/><path class="cjtmbcfpi"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:resort-outline-bold" {...props}></Icon>
<style>
:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.cjtmbcfpi) {
  d: path("M13 18v-7h9v7");
}

:global(.ghuq2xb5p) {
  d: path("M10.5 12.5a3.5 3.5 0 0 1 0 -7");
}

:global(.k4wc6x-hq) {
  d: path("M7 9v9");
}

:global(.n_xjdobth) {
  d: path("M3.5 5.5a3.5 3.5 0 0 1 0 7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
