<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="onhg5sb4f"/><circle class="do29zw4qy"/><path class="d-uz2lspu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pendulum-balls-sharp" {...props}></Icon>
<style>
:global(.d-uz2lspu) {
  d: path("M7.34 20.14A18 18 0 0 0 21 18.34");
}

:global(.do29zw4qy) {
  cx: 17.49px;
  cy: 14.53px;
  r: 2.5px;
}

:global(.onhg5sb4f) {
  d: path("M8.25 2.75h7.5m-3.75 0l4.44 9.52");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
