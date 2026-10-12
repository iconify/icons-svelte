<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="sd6wdsdpf"/><path class="xe5njdbqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:retort-sharp" {...props}></Icon>
<style>
:global(.sd6wdsdpf) {
  cx: 8.75px;
  cy: 14.5px;
  r: 6px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xe5njdbqo) {
  d: path("M2.95 16h11.6M13 10.25c1.5-4.75 3.75-6.5 5.25-4.5l3 7.25");
}

</style>
