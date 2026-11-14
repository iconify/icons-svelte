<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pxowz7n_c"/><path class="is8nqnbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:date-rotation" {...props}></Icon>
<style>
:global(.is8nqnbzt) {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

:global(.pxowz7n_c) {
  d: path("M12.562 19.5H2.5v-13l2-3.5h13l2 3.5v6.438M2.5 6.5h17m-8.5 0v4m9.75 8A2.75 2.75 0 1 1 18 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
