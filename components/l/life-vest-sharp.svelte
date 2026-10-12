<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="biat8jiuu"/><path class="num2www6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:life-vest-sharp" {...props}></Icon>
<style>
:global(.biat8jiuu) {
  d: path("m8.5 3.25l-3.75 2.5v15.5h14.5V5.75l-3.75-2.5L12 8.5ZM12 8.5v3m0 4.5v5.25m-7.25-8h5m4.5 0h5");
}

:global(.num2www6o) {
  d: path("M9.75 11.75h4.5v3h-4.5z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
