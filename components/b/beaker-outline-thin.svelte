<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z26jhbbft"/><path class="z8g2jgblp"/><path class="jyz8nlkxs"/><path class="dpjt_8byn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beaker-outline-thin" {...props}></Icon>
<style>
:global(.dpjt_8byn) {
  d: path("M17 5h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jyz8nlkxs) {
  d: path("M3 5h4");
}

:global(.z26jhbbft) {
  d: path("M5 5v15h14V5");
}

:global(.z8g2jgblp) {
  d: path("M5 12h14");
}

</style>
