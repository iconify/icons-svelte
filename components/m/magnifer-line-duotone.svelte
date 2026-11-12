<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGcfiNQVot"><g class="k2u665ban"><circle class="b4dyhhbeb"/><path class="fo97hvbjm"/></g></mask></defs><path mask="url(#SVGcfiNQVot)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifer-line-duotone" {...props}></Icon>
<style>
:global(.b4dyhhbeb) {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  stroke: var(--svg-color--gray, gray);
}

:global(.fo97hvbjm) {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  d: path("M18.5 18.5L22 22");
}

:global(.k2u665ban) {
  fill: none;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w49j0rbvv) {
  fill: currentColor;
  d: path("M0 0h24v24H0z");
}

</style>
