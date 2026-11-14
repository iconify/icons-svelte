<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ngem3yi1y"/><path class="jn2xvdyup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:road-narrows-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jn2xvdyup) {
  d: path("M9 17.75v-2.5l1.5-2V11m4.5 6.75v-2.5l-1.5-2V11");
}

:global(.ngem3yi1y) {
  d: path("m14.308 6.761l5.343 9.864a2.625 2.625 0 0 1-2.308 3.875H6.657a2.625 2.625 0 0 1-2.308-3.875l5.343-9.864a2.625 2.625 0 0 1 4.616 0");
}

</style>
