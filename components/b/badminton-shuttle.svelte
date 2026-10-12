<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l894-tb2h"/><path class="j4g21fbob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:badminton-shuttle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4g21fbob) {
  d: path("M9 15.5h6v2.75a3 3 0 0 1-6 0Z");
}

:global(.l894-tb2h) {
  d: path("M6.75 2.75h10.5q1 0 .75.97l-2.75 10.81q-.25.97-1.25.97h-4q-1 0-1.25-.97L6 3.72q-.25-.97.75-.97M12 15.5V2.75m-5.15 4.5h10.3");
}

</style>
