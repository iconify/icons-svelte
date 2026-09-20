<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cjwmwb6_i"/><path class="jotk81b5q"/><path class="rqm7ypbhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:baggage-drop-outline-thin" {...props}></Icon>
<style>
:global(.cjwmwb6_i) {
  d: path("M3 12a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jotk81b5q) {
  d: path("M12 2v6");
}

:global(.rqm7ypbhc) {
  d: path("M9.5 5.5 12 8l2.5 -2.5");
}

</style>
