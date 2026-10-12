<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n475r60ru"/><path class="uss5p5bfd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lavender" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n475r60ru) {
  d: path("M12 2.75c1.5 1 2.25 2.75 2.25 4.75V11c0 1.25-1 2.25-2.25 2.25s-2.25-1-2.25-2.25V7.5c0-2 .75-3.75 2.25-4.75");
}

:global(.uss5p5bfd) {
  d: path("M9.75 8.25L12 9.75l2.25-1.5m-2.25 5v8m0-2.5c-1.5-.5-3-2-3.5-3.75m3.5 2.25c1.5-.5 2.75-1.75 3.25-3.25");
}

</style>
