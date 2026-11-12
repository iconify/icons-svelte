<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG2GlueH5m"><g class="k2u665ban"><circle class="b4dyhhbeb"/><path class="n8qh-cn0s"/></g></mask></defs><path mask="url(#SVG2GlueH5m)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifer-zoom-in-line-duotone" {...props}></Icon>
<style>
:global(.b4dyhhbeb) {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  stroke: var(--svg-color--gray, gray);
}

:global(.k2u665ban) {
  fill: none;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n8qh-cn0s) {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  d: path("M18.5 18.5L22 22M9 11.5h2.5m0 0H14m-2.5 0V14m0-2.5V9");
}

:global(.w49j0rbvv) {
  fill: currentColor;
  d: path("M0 0h24v24H0z");
}

</style>
