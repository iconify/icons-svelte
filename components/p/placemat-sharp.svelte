<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fha6990wp"/><path class="l6o-ek34l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:placemat-sharp" {...props}></Icon>
<style>
:global(.fha6990wp) {
  d: path("M2.75 4.75h18.5v14.5H2.75z");
}

:global(.l6o-ek34l) {
  d: path("M12 8.75a3.25 3.25 0 1 1 0 6.5a3.25 3.25 0 1 1 0-6.5Zm-6.25 0v6.5m12.5-6.5v6.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
