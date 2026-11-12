<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><circle class="q5a2teajs"/><circle class="o7l51rbax"/><path class="ituo-kbtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bowling-line-duotone" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ituo-kbtq) {
  d: path("M8 8C8.82843 8 9.5 8.67157 9.5 9.5C9.5 10.3284 8.82843 11 8 11C7.17157 11 6.5 10.3284 6.5 9.5C6.5 8.67157 7.17157 8 8 8Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.o7l51rbax) {
  cx: 12px;
  cy: 12px;
  r: 1.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.q5a2teajs) {
  cx: 12px;
  cy: 7px;
  r: 1.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.shu3xdl9q) {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

</style>
