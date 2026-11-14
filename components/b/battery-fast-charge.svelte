<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ub29l-bqr"/><path class="jbmt-ydqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battery-fast-charge" {...props}></Icon>
<style>
:global(.jbmt-ydqg) {
  d: path("m13.25 9l-2 3h3l-2 3M5.5 10.5h3.25m-3.25 3h2.25");
}

:global(.ub29l-bqr) {
  d: path("M2.5 7H19v10H2.5Zm19 3.5v3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
