<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crv4i00bu"/><path class="ma5mp6b8k"/><path class="wihdixnjz"/><path class="q6r-ungsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:posture-outline-thin" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ma5mp6b8k) {
  d: path("M11 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.q6r-ungsl) {
  d: path("m10 19 4 -4 4 4");
}

:global(.wihdixnjz) {
  d: path("M14 9v6");
}

</style>
