<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qucxf5b3s"/><path class="k0-4f4ccs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mailbox-sensor" {...props}></Icon>
<style>
:global(.k0-4f4ccs) {
  d: path("m2.5 8.5l6 4l6-4");
}

:global(.qucxf5b3s) {
  d: path("M2.5 7h12v10h-12Zm14.75 3.25a2.5 2.5 0 0 1 0 3.5M19.75 8a5 5 0 0 1 0 8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
