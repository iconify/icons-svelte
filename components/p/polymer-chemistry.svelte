<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5qodgb2v"/><path class="tfuperbnz"/><path class="fv1uhpbyq"/><path class="ooua5kb7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:polymer-chemistry" {...props}></Icon>
<style>
:global(.f5qodgb2v) {
  d: path("m2.739 13.73l3.612-5.405a1.75 1.75 0 0 1 2.427-.482a1.75 1.75 0 0 1 .483 2.427l-3.612 5.405a1.75 1.75 0 0 1-2.427.482a1.75 1.75 0 0 1-.483-2.427");
}

:global(.fv1uhpbyq) {
  d: path("m10.739 13.73l3.612-5.405a1.75 1.75 0 0 1 2.427-.482a1.75 1.75 0 0 1 .483 2.427l-3.612 5.405a1.75 1.75 0 0 1-2.427.482a1.75 1.75 0 0 1-.483-2.427");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ooua5kb7v) {
  d: path("m17.649 8.325l3.612 5.405a1.75 1.75 0 0 1-.483 2.427a1.75 1.75 0 0 1-2.427-.482l-3.612-5.405a1.75 1.75 0 0 1 .483-2.427a1.75 1.75 0 0 1 2.427.482");
}

:global(.tfuperbnz) {
  d: path("m9.649 8.325l3.612 5.405a1.75 1.75 0 0 1-.483 2.427a1.75 1.75 0 0 1-2.427-.482L6.739 10.27a1.75 1.75 0 0 1 .483-2.427a1.75 1.75 0 0 1 2.427.482");
}

</style>
