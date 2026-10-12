<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e9-7-8-2z"/><path class="ltyaddk2c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:person-standing-sharp" {...props}></Icon>
<style>
:global(.e9-7-8-2z) {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

:global(.ltyaddk2c) {
  d: path("M12 9.5v6.25m-2.5 5.5l2.5-5.5l2.5 5.5m-6.75-6.5L9.25 10h5.5l1.5 4.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
