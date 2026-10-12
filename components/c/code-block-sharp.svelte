<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="ozas_ibsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:code-block-sharp" {...props}></Icon>
<style>
:global(.ozas_ibsg) {
  d: path("m8.75 8.75l-3 3.25l3 3.25m6.5-6.5l3 3.25l-3 3.25m-2.5-6.75l-1.5 7");
}

:global(.pw7p-85ys) {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
