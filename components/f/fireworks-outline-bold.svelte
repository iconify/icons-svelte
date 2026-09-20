<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ux6apgnet"/><path class="u6ltz0bsa"/><path class="z5j-qdr3m"/><path class="hsrzt0bgt"/><path class="o5ex3bb1u"/><path class="lnxxf4b_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fireworks-outline-bold" {...props}></Icon>
<style>
:global(.hsrzt0bgt) {
  d: path("m10 8 3 -3");
}

:global(.lnxxf4b_g) {
  d: path("m19 19 2 2");
}

:global(.o5ex3bb1u) {
  d: path("M16 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u6ltz0bsa) {
  d: path("M8 7V4");
}

:global(.ux6apgnet) {
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.z5j-qdr3m) {
  d: path("M6 8 3 5");
}

</style>
