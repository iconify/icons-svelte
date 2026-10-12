<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m7a683b3w"/><path class="poz69lb7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:property-tax-sharp" {...props}></Icon>
<style>
:global(.m7a683b3w) {
  d: path("M6.5 2.75h12.25v18.5l-2.25-1.5l-2.25 1.5l-2.25-1.5l-2.25 1.5l-2.25-1.5l-2.25 1.5V2.75z");
}

:global(.poz69lb7r) {
  d: path("M9 11.15V8.5l.46-.38l2.08-1.74L12 6l.46.38l2.08 1.74l.46.38v3.25H9zM8.5 15h7");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
