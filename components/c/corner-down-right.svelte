<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skkiwmb7k"/><path class="hynzddbgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:corner-down-right" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hynzddbgn) {
  d: path("m15.5 11l3.75 3.75l-3.75 3.75");
}

:global(.skkiwmb7k) {
  d: path("M4.25 4.25v8a2.5 2.5 0 0 0 2.5 2.5h12.5");
}

</style>
