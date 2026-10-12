<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wijmr5spd"/><path class="yg4503prc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:person-reading" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wijmr5spd) {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

:global(.yg4503prc) {
  d: path("M12 13c-1.75-1.25-4-1.75-7.25-1.75v7.5c3.25 0 5.5.5 7.25 1.75c1.75-1.25 4-1.75 7.25-1.75v-7.5c-3.25 0-5.5.5-7.25 1.75m0 .25v6.5");
}

</style>
