<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ttdy-b6jx"/><path class="laupq6byw"/><circle class="yfr-mbcnn"/><path class="nomrmkbdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:partnership-sharp" {...props}></Icon>
<style>
:global(.laupq6byw) {
  d: path("M4 20.25h6.75v-.75c0-2.9-1.7-5-3.75-5s-3.75 2.1-3.75 5v.75z");
}

:global(.nomrmkbdu) {
  d: path("M14 20.25h6.75v-.75c0-2.9-1.7-5-3.75-5s-3.75 2.1-3.75 5v.75z");
}

:global(.ttdy-b6jx) {
  cx: 7px;
  cy: 7.5px;
  r: 3px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yfr-mbcnn) {
  cx: 17px;
  cy: 7.5px;
  r: 3px;
}

</style>
