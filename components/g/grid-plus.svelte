<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jh4-22bkf"/><path class="wtird7qzy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:grid-plus" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jh4-22bkf) {
  d: path("M13.373 20.273L12 21l-8.5-4.5v-9L12 3l8.5 4.5v6.265");
}

:global(.wtird7qzy) {
  d: path("M3.5 7.5L12 12l8.5-4.5M12 12v9M9.25 3.5v17M3.5 9.25h17M14.75 3.5v5.75m-5.5 5.5h3M18 15v6m-3-3h6");
}

</style>
