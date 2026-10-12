<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u-2eaqa5y"/><circle class="n4tbcbbac"/><circle class="yssow-b-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:emissions-stack-sharp" {...props}></Icon>
<style>
:global(.n4tbcbbac) {
  cx: 11px;
  cy: 5.25px;
  r: 2.5px;
}

:global(.u-2eaqa5y) {
  d: path("m5.1 20.51l1.3-9.77l.1-.74h4l.1.74l1.3 9.77l.1.74H5zM6.25 14h4.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yssow-b-l) {
  cx: 18.5px;
  cy: 5px;
  r: 2px;
}

</style>
