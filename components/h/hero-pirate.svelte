<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eepl8cc-i"/><path class="ywtk4ubnc"/><path class="g4amvs9gp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hero-pirate" {...props}></Icon>
<style>
:global(.eepl8cc-i) {
  d: path("m4.5 6.75l1.225-1.684a1.75 1.75 0 0 1 2.013-.616l3.664 1.333a1.75 1.75 0 0 0 1.196 0l3.664-1.333a1.75 1.75 0 0 1 2.013.616L19.5 6.75a1.732 1.732 0 0 1-1.4 2.75H5.9a1.732 1.732 0 0 1-1.4-2.75m2 2.75V14a5.5 5.5 0 0 0 11 0V9.5");
}

:global(.g4amvs9gp) {
  d: path("m6.5 12.5l5.5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ywtk4ubnc) {
  fill: currentColor;
  d: path("M12 13.25a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0");
}

</style>
