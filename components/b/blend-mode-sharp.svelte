<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ekggvtblj"/><circle class="v1ocdgb7u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blend-mode-sharp" {...props}></Icon>
<style>
:global(.ekggvtblj) {
  cx: 8.75px;
  cy: 12px;
  r: 6px;
}

:global(.v1ocdgb7u) {
  cx: 15.25px;
  cy: 12px;
  r: 6px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
