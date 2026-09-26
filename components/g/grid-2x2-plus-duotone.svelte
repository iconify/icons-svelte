<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pq89r888z"/><path class="yrxuhgb1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-2x2-plus-duotone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pq89r888z) {
  stroke-opacity: 0.4;
  d: path("M2 11H18C19.1046 11 20 10.1046 20 9V5C20 3.3431 18.6569 2 17 2H5C3.3431 2 2 3.3431 2 5V17C2 18.6569 3.3431 20 5 20H9C10.1046 20 11 19.1046 11 18V2");
}

:global(.yrxuhgb1c) {
  d: path("M19 16L19 22M16 19L22 19");
}

</style>
