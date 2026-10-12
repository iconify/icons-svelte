<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="c4sg-rw9q"/><path class="h17i4ccng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lavender-sharp" {...props}></Icon>
<style>
:global(.c4sg-rw9q) {
  d: path("m12 2.75l2.25 1.5v9h-4.5v-9z");
}

:global(.h17i4ccng) {
  d: path("M9.75 8.25L12 9.75l2.25-1.5m-2.25 5v8m0-2.5l-2.684-.895L8.5 15m3.5 2.25l2.438-.812L15.25 14");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
