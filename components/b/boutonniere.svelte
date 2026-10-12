<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="q3-to6b0w"/><path class="z9nu0g-jq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boutonniere" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q3-to6b0w) {
  cx: 15px;
  cy: 9px;
  r: 5.25px;
}

:global(.z9nu0g-jq) {
  d: path("M12.75 9A2.25 2.25 0 1 0 15 6.75m-5.5 9c-3.5 0-5.75-2-6.25-4.75c3 0 5.5 1.5 6.25 4.75m1.75-3L5 19m.25-2L12 21.25");
}

</style>
