<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mu7698bfs"/><path class="mhr6r2bqa"/><circle class="j5pu4cbfj"/><path class="ev0opqbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ektara-sharp" {...props}></Icon>
<style>
:global(.ev0opqbry) {
  d: path("m15.08 3.64l2.58.94m-2.58-.94l-3.34 9.16");
}

:global(.j5pu4cbfj) {
  cx: 10.38px;
  cy: 16.56px;
  r: 1px;
}

:global(.mhr6r2bqa) {
  d: path("M8.68 12.94c1.12-4.3 2.92-9.23 6.4-9.3");
}

:global(.mu7698bfs) {
  cx: 10.38px;
  cy: 16.56px;
  r: 4px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
