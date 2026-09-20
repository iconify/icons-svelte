<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="flq2w3bwj"/><path class="k5f0ncbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:feature-cross-outline-thin" {...props}></Icon>
<style>
:global(.flq2w3bwj) {
  d: path("m9.5 9.5 5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k5f0ncbhf) {
  d: path("m14.5 9.5 -5 5");
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.t3rq50btb) {
  d: path("M19 4v16");
}

</style>
