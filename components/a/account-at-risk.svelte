<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wbfivcc8o"/><path class="lo970fxfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:account-at-risk" {...props}></Icon>
<style>
:global(.lo970fxfb) {
  d: path("M8 21.5V17h3v4.5M7 7h.01M12 7h.01M7 11.5h.01m4.99 0h.01m6.99 3V18m0 3h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wbfivcc8o) {
  d: path("M3 2.5h13v19H3Z");
}

</style>
