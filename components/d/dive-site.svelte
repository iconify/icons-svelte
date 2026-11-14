<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bzzx5hq_k"/><path class="irzukcl2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dive-site" {...props}></Icon>
<style>
:global(.bzzx5hq_k) {
  d: path("M12 19c-3.5-4-6.5-7-6.5-10a6.5 6.5 0 0 1 13 0c0 3-3 6-6.5 10Z");
}

:global(.irzukcl2o) {
  d: path("M9.5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-7 10q1.5-2 3 0t3 0m7 0q1.5-2 3 0t3 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
