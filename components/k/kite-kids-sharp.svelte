<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lhvuz1bim"/><circle class="t9sqlg7hc"/><path class="v6qhv1bxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kite-kids-sharp" {...props}></Icon>
<style>
:global(.lhvuz1bim) {
  d: path("m17.53 3.28l3.19 3.19l.53.53l-.53.53l-3.19 3.19l-.53.53l-.53-.53l-3.19-3.19l-.53-.53l.53-.53l3.19-3.19l.53-.53zM17 11.25c0 3-4 3-8 5");
}

:global(.t9sqlg7hc) {
  cx: 6.25px;
  cy: 10.75px;
  r: 2.25px;
}

:global(.v6qhv1bxz) {
  d: path("M3 21.25v-2.5a3.25 3.25 0 0 1 6.5 0v2.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
