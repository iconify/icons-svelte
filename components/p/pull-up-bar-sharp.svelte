<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="askjmlbex"/><circle class="sdggh2xtg"/><path class="qx7xrvl5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pull-up-bar-sharp" {...props}></Icon>
<style>
:global(.askjmlbex) {
  d: path("M2.75 3h18.5");
}

:global(.qx7xrvl5u) {
  d: path("m5.5 3l4 7.5h5l4-7.5M12 10.5V15m0 0l-1.25 6.25M12 15l1.25 6.25");
}

:global(.sdggh2xtg) {
  cx: 12px;
  cy: 6.75px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
