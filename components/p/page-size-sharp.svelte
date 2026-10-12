<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="utiyf1bym"/><path class="kcirip0ot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:page-size-sharp" {...props}></Icon>
<style>
:global(.kcirip0ot) {
  d: path("m8.75 17.75l5-5m-5 1.5v3.5h3.5m1.5-1.5v-3.5h-3.5");
}

:global(.utiyf1bym) {
  d: path("M14.25 2.75h-9v18.5h13.5v-14zm0 0v4.5h4.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
