<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uadei4m8s"/><path class="o3z3j5btx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boarding-gate-sharp" {...props}></Icon>
<style>
:global(.o3z3j5btx) {
  d: path("M8.75 16.25H15m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

:global(.uadei4m8s) {
  d: path("M2.75 2.75h18.5v5H2.75zm3.5 2.5h4.5m3 0h4m-12.5 16v-10h13.5v10");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
