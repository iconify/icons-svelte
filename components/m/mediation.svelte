<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="om__bzh9z"/><path class="ptdmkpbch"/><circle class="nbp9vlbqw"/><path class="llilh5ddm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mediation" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.llilh5ddm) {
  d: path("M15.25 19.5a3 5.25 0 0 1 6 0M9.75 12h4.5M12 12v7.5");
}

:global(.nbp9vlbqw) {
  cx: 18.25px;
  cy: 8.5px;
  r: 2.5px;
}

:global(.om__bzh9z) {
  cx: 5.75px;
  cy: 8.5px;
  r: 2.5px;
}

:global(.ptdmkpbch) {
  d: path("M2.75 19.5a3 5.25 0 0 1 6 0");
}

</style>
