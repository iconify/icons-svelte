<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="f9xu_cb8q"/><circle class="dxajnmbvk"/><circle class="tyhetpb4e"/><path class="fygqrlb-u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:git-fork-sharp" {...props}></Icon>
<style>
:global(.dxajnmbvk) {
  cx: 17.5px;
  cy: 5.25px;
  r: 2.25px;
}

:global(.f9xu_cb8q) {
  cx: 6.5px;
  cy: 5.25px;
  r: 2.25px;
}

:global(.fygqrlb-u) {
  d: path("M6.5 7.5v4.25h11V7.5M12 11.75v4.5");
}

:global(.tyhetpb4e) {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
