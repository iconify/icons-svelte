<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w4d1lwbew"/><path class="k2jt89bee"/><path class="t71cp2bqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:help-widget" {...props}></Icon>
<style>
:global(.k2jt89bee) {
  d: path("M12 17a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

:global(.t71cp2bqs) {
  d: path("M15.5 15.75a1.5 1.5 0 0 1 3 0c0 1-1.5 1.25-1.5 2M17 20h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w4d1lwbew) {
  d: path("M9.2 16.5H2.5v-14H19v6.9M6 7.5h9.5m-9.5 4h4.5");
}

</style>
