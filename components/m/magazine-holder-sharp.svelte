<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="aeeh76pet"/><path class="y83m_hi6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:magazine-holder-sharp" {...props}></Icon>
<style>
:global(.aeeh76pet) {
  d: path("M4.75 19.75v-8l1.06-1.06l6.88-6.88l1.06-1.06h5.5v18.5H4.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y83m_hi6j) {
  d: path("M8.25 14.25h7.5v4h-7.5z");
}

</style>
