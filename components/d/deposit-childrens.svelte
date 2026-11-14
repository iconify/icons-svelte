<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jmz0z3evc"/><path class="nyfgqbqtt"/><path class="mtyzu8y-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deposit-childrens" {...props}></Icon>
<style>
:global(.jmz0z3evc) {
  d: path("M11.945 18c-.72 0-1.213-.006-1.945-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6c4.461 0 7.939 2.457 7.999 5.909");
}

:global(.mtyzu8y-f) {
  d: path("m16.5 19.75l1.5-3.5l1.5 3.5");
}

:global(.nyfgqbqtt) {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m1.25 6.25h6.5v6.5h-6.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
