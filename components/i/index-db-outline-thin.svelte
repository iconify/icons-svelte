<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iaozfqbuj"/><path class="jlpxneb5g"/><path class="yr3fnb1ar"/><path class="wdz1ifmrg"/><path class="xsa445osm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:index-db-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iaozfqbuj) {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

:global(.jlpxneb5g) {
  d: path("M9 8v8");
}

:global(.wdz1ifmrg) {
  d: path("M9 12h7");
}

:global(.xsa445osm) {
  d: path("M9 15h7");
}

:global(.yr3fnb1ar) {
  d: path("M9 9h7");
}

</style>
