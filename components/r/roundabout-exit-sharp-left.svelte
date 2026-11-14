<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fhdmpm8re"/><path class="gnxbd7fhv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:roundabout-exit-sharp-left" {...props}></Icon>
<style>
:global(.fhdmpm8re) {
  d: path("M13.25 21.5v-7a5 5 0 1 0-3.5-1.5l-4 4");
}

:global(.gnxbd7fhv) {
  d: path("M9 17H5.75v-3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
