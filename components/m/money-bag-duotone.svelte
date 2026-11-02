<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zwh6a7bki"/><path class="q3i4wbcok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:money-bag-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.q3i4wbcok) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 8l5 5c.64.64 1 1.72 1 3v2a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-2c0-1.28.36-2.36 1-3l5-5l-3-5h8zm-3 0h4");
}

:global(.zwh6a7bki) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m14.259 7.845l4.448 4.448C19.665 13.252 20 14.683 20 16v2a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4v-2c0-1.317.335-2.748 1.293-3.707l4.448-4.448l-2.598-4.331A.997.997 0 0 1 8 2h8a1 1 0 0 1 .857 1.514Z");
}

</style>
