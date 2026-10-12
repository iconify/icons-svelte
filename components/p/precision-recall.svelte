<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bq2hshbed"/><circle class="p8mues6hm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:precision-recall" {...props}></Icon>
<style>
:global(.bq2hshbed) {
  d: path("M3.25 3.25v17.5h17.5M6.25 6.25h7m3 .15c1.5.6 2.4 4.35 3 11.1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p8mues6hm) {
  cx: 14.75px;
  cy: 6.25px;
  r: 1.5px;
}

</style>
