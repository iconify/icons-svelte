<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="svo38jbaa"/><path class="vq2y_z06k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mango-lassi" {...props}></Icon>
<style>
:global(.svo38jbaa) {
  d: path("m6.5 5l1 16h9l1-16M6.75 9h10.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vq2y_z06k) {
  d: path("m13.5 9l2-6.5H13");
}

</style>
