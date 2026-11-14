<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wjdlwcr7g"/><path class="u2o19gb-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:presentation-target" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u2o19gb-a) {
  d: path("M8.75 9a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M12 9h.01");
}

:global(.wjdlwcr7g) {
  d: path("M5.625 3h12.75A2.625 2.625 0 0 1 21 5.625v6.75A2.625 2.625 0 0 1 18.375 15H5.625A2.625 2.625 0 0 1 3 12.375v-6.75A2.625 2.625 0 0 1 5.625 3M12 15v6m0-6l-5 6m5-6l5 6");
}

</style>
