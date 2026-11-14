<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dircedbbw"/><path class="ay2f4rb_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:baseball-base" {...props}></Icon>
<style>
:global(.ay2f4rb_p) {
  d: path("M2.5 11v3l9.5 5l9.5-5v-3M12 16v3");
}

:global(.dircedbbw) {
  d: path("M2.5 11L12 6l9.5 5l-9.5 5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
