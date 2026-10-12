<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jbkmw0n6j"/><path class="oxwicob_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:check-in-pin-sharp" {...props}></Icon>
<style>
:global(.jbkmw0n6j) {
  d: path("M12 21.25S5 15.5 5 9.75a7 7 0 0 1 14 0c0 5.75-7 11.5-7 11.5Z");
}

:global(.oxwicob_u) {
  d: path("m9 9.75l2 2l4-4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
