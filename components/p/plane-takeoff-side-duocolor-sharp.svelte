<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="obqscbcxp"/><path class="wyuiwlbdo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plane-takeoff-side-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.obqscbcxp) {
  stroke-opacity: 0.4;
  d: path("M3 21h18");
}

:global(.wyuiwlbdo) {
  d: path("m7 13l2-1l-2.553-5.106a1 1 0 0 1 .447-1.341l.461-.23a1 1 0 0 1 1.155.187L13 10l6.553-3.276A1 1 0 0 1 21 7.618v1.764a1 1 0 0 1-.553.894L7.211 16.894a1 1 0 0 1-.447.106H5.618a1 1 0 0 1-.894-.553l-1-2A1 1 0 0 1 4.618 13z");
}

</style>
