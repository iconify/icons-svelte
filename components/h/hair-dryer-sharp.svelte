<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mius_obps"/><path class="m2--chbrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hair-dryer-sharp" {...props}></Icon>
<style>
:global(.m2--chbrv) {
  d: path("M8.75 8.25a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 1 1 3.5 0m-1 7h3.75l-.21 1.23l-.58 3.54l-.21 1.23h-4v-6z");
}

:global(.mius_obps) {
  d: path("M2.75 4.25h12.5v8H2.75zm15.5 1.5h3v5h-3z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
