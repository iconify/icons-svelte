<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z81so0b2c"/><circle class="ff2w_2bef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:joint-knee-sharp" {...props}></Icon>
<style>
:global(.ff2w_2bef) {
  cx: 19.75px;
  cy: 13px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z81so0b2c) {
  d: path("M9.5 2.75h5v6l2.5.417V11.5H7V9.167l2.5-.417ZM7 14.5h10v2.333l-2.5.417v4h-5v-4L7 16.833V14.75Z");
}

</style>
