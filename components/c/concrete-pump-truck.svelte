<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ftnaqly3h"/><path class="iyo8z0bpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:concrete-pump-truck" {...props}></Icon>
<style>
:global(.ftnaqly3h) {
  d: path("M2.5 16.5v-3h12v-5h4l3 3.5v4.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iyo8z0bpt) {
  d: path("m4.5 13.5l3-10l4.25 3.75L19.5 3v3m-15 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
