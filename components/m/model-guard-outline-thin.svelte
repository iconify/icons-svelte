<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ag6e_acqq"/><path class="psf2kha1z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-guard-outline-thin" {...props}></Icon>
<style>
:global(.ag6e_acqq) {
  d: path("M6 6.5 9.5 10 6 13.5 2.5 10Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.psf2kha1z) {
  d: path("M13 11h9v5.5L17.5 21 13 16.5Z");
}

</style>
