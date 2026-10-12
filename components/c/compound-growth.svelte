<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmvt8fbnf"/><path class="ey5a1cbqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:compound-growth" {...props}></Icon>
<style>
:global(.ey5a1cbqn) {
  d: path("M6.5 17.25c5.5-.25 10-3.75 12.75-13m-2.53 1.1l2.53-1.1l1.1 2.53");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qmvt8fbnf) {
  d: path("M3.25 3.25v17.5h17.5");
}

</style>
