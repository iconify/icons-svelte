<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ik0twvfwg"/><path class="ni6nfmb8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:captcha-sharp" {...props}></Icon>
<style>
:global(.ik0twvfwg) {
  d: path("M2.75 2.75h7.75v7.75H2.75zm10.75 0h7.75v7.75H13.5zM2.75 13.5h7.75v7.75H2.75zm10.75 0h7.75v7.75H13.5z");
}

:global(.ni6nfmb8z) {
  d: path("m15.5 6.75l1.5 1.5l2.5-2.75m-14.75 12l1.5 1.5l2.5-2.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
