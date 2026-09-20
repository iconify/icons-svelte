<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zu4ajq05m"/><path class="eqqc-z5sv"/><path class="q88myjbfp"/><path class="va4lqxm9h"/><path class="fqg-d6bob"/><path class="plef9ibei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:region-pair-outline-thin" {...props}></Icon>
<style>
:global(.eqqc-z5sv) {
  d: path("M3 6.5h7");
}

:global(.fqg-d6bob) {
  d: path("M14 17.5h7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.plef9ibei) {
  d: path("M17.5 14v7");
}

:global(.q88myjbfp) {
  d: path("M6.5 3v7");
}

:global(.va4lqxm9h) {
  d: path("M13.5 17.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.zu4ajq05m) {
  d: path("M2.5 6.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
