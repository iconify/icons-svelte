<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1ko8xruq"/><path class="jo34ko0tj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:compliance-shield" {...props}></Icon>
<style>
:global(.g1ko8xruq) {
  d: path("M12 2.5c2.5 2 5 2.5 8 2.5v6.5c0 4.5-3.5 8-8 10c-4.5-2-8-5.5-8-10V5c3 0 5.5-.5 8-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jo34ko0tj) {
  d: path("m8.5 12l2.5 2.5l4.5-4.5");
}

</style>
