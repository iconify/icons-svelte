<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wvgz1hbla"/><rect class="z3272ig5b"/><path class="nyt3xcpfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fishing-boat" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nyt3xcpfn) {
  d: path("m12.5 12.5l6-9.25m0 0L20.75 9m0 0v1.25a1 1 0 0 1-2 0m-16 11c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

:global(.wvgz1hbla) {
  d: path("M2.75 12.5h18.5l-1.75 3.9a1.75 1.75 0 0 1-1.62 1.1H6.12a1.75 1.75 0 0 1-1.62-1.1Z");
}

:global(.z3272ig5b) {
  width: 4.5px;
  height: 4.25px;
  x: 5.5px;
  y: 8.25px;
  rx: 0.75px;
}

</style>
