<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4i4nt1-g"/><path class="c7oxexnqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kids-bed" {...props}></Icon>
<style>
:global(.c7oxexnqh) {
  d: path("M9.5 10H16v3");
}

:global(.f4i4nt1-g) {
  d: path("M3.5 19V8.5a3 3 0 0 1 6 0V13h11v6m-17-2.5h17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
