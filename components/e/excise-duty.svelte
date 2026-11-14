<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ra377whpp"/><path class="px48ufb1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:excise-duty" {...props}></Icon>
<style>
:global(.px48ufb1m) {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v8.6m2.75 1.15l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

:global(.ra377whpp) {
  d: path("M11.059 21.002L3.5 17V7L12 2.5L20.5 7v4.582");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
