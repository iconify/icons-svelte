<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v563j7avx"/><circle class="ukvmc8bfw"/><path class="ziql97jnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:portfolio-sharp" {...props}></Icon>
<style>
:global(.ukvmc8bfw) {
  cx: 12px;
  cy: 14px;
  r: 4px;
}

:global(.v563j7avx) {
  d: path("M9 7V4h6v3M3 7h18v14H3z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ziql97jnu) {
  d: path("M12 10v4h4");
}

</style>
