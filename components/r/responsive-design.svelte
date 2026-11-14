<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v3q17vbkw"/><path class="nicb36bun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:responsive-design" {...props}></Icon>
<style>
:global(.nicb36bun) {
  d: path("M15.5 9h6v12h-6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v3q17vbkw) {
  d: path("M12.7 15H2.5V3.5h15v2.7M10 15v4m-2.75 0h5.4");
}

</style>
