<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e0newffle"/><path class="nrwhfkuns"/><path class="mzs9lvbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:export-control-outline-thin" {...props}></Icon>
<style>
:global(.e0newffle) {
  d: path("M3 10a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mzs9lvbbs) {
  d: path("M19.5 4v16");
}

:global(.nrwhfkuns) {
  d: path("M14 12h2.5");
}

</style>
