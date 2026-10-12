<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gjnph2f5p"/><path class="ev1uqxt7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cube-sharp" {...props}></Icon>
<style>
:global(.ev1uqxt7k) {
  d: path("m4.5 7.75l7.5 4l7.5-4m-7.5 4v8.5");
}

:global(.gjnph2f5p) {
  d: path("m13.32 3.47l5.61 3.06l1.32.72v9.5l-1.32.72l-5.61 3.06l-1.32.72l-1.32-.72l-5.61-3.06l-1.32-.72v-9.5l1.32-.72l5.61-3.06L12 2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
