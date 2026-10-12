<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fha6990wp"/><path class="extlghybi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kpi-arrow-sharp" {...props}></Icon>
<style>
:global(.extlghybi) {
  d: path("M8.25 15V8.5M5.5 11.25L8.25 8.5L11 11.25M13.75 10h4m-4 4h2.5");
}

:global(.fha6990wp) {
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
