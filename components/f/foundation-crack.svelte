<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lbma92bjw"/><path class="k-3ptfbsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:foundation-crack" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-3ptfbsx) {
  d: path("m11 4l2 4.5l-2.5 3.5l3 3.5l-2 4.5");
}

:global(.lbma92bjw) {
  d: path("M4.25 4h15.5a1.75 1.75 0 0 1 1.75 1.75v12.5A1.75 1.75 0 0 1 19.75 20H4.25a1.75 1.75 0 0 1-1.75-1.75V5.75A1.75 1.75 0 0 1 4.25 4");
}

</style>
