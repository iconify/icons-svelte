<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="youqy3w_k"/><path class="uw2efubnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grief" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uw2efubnl) {
  d: path("M14 6.75a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 1.5 2.5a1.5 1.5 0 0 1-1.5 2.5a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1-1.5-2.5a1.5 1.5 0 0 1 1.5-2.5ZM7 16c-2.5 0-4-1.5-4-3.5c2.5 0 4 1.5 4 3.5Zm8.5 0c1.5 2 1.75 2.75 1.75 3.5a1.75 1.75 0 0 1-3.5 0c0-.75.25-1.5 1.75-3.5Z");
}

:global(.youqy3w_k) {
  d: path("M7 21.5V11c0-5 2.5-7.5 6-7.5c1.5 0 2.5.75 2.5 1.75");
}

</style>
