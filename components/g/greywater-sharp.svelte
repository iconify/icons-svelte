<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b465ubb6t"/><path class="eynti2bpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:greywater-sharp" {...props}></Icon>
<style>
:global(.b465ubb6t) {
  d: path("M20.5 12a8.5 8.5 0 1 1-2.49-6.01m0-2.99v3h-3");
}

:global(.eynti2bpg) {
  d: path("M12 7.5c2 2.3 3.25 4 3.25 5.75a3.25 3.25 0 0 1-6.5 0C8.75 11.5 10 9.8 12 7.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
