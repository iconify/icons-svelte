<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zfqqr8bin"/><path class="enzqy_ond"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:anonymous-source" {...props}></Icon>
<style>
:global(.enzqy_ond) {
  d: path("M9 11a3 3.75 0 1 0 6 0a3 3.75 0 1 0-6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zfqqr8bin) {
  d: path("M3.5 21.5V20c0-2.5 1.5-4 2.5-4.5V10c0-4 3-6.5 6-7.5c3 1 6 3.5 6 7.5v5.5c1 .5 2.5 2 2.5 4.5v1.5Z");
}

</style>
