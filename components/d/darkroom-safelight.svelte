<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lcs5lo0kt"/><path class="fei8yg9-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:darkroom-safelight" {...props}></Icon>
<style>
:global(.fei8yg9-b) {
  d: path("M7.75 5.75h8.5v4.5h-8.5ZM12 16v5m-4.5-5.5l-2 4m11-4l2 4");
}

:global(.lcs5lo0kt) {
  d: path("M5 3h14v10H5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
