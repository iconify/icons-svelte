<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fha6990wp"/><path class="ydyxs3b_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mail-pin-sharp" {...props}></Icon>
<style>
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

:global(.ydyxs3b_d) {
  d: path("m6.5 8.75l4.1 3.1l1.4.988l1.4-.988l4.1-3.1");
}

</style>
