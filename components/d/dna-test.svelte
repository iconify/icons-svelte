<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lnnprcbev"/><path class="b-h2u6bwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dna-test" {...props}></Icon>
<style>
:global(.b-h2u6bwx) {
  d: path("M10 7.5c0 2.75 4 2.75 4 5.5s-4 2.75-4 5.5m4-11c0 2.75-4 2.75-4 5.5s4 2.75 4 5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lnnprcbev) {
  d: path("M6.75 4.75h10.5m-9.75 0h9v12a4.5 4.5 0 0 1-9 0Z");
}

</style>
