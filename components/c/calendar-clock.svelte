<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sa23nmb2h"/><path class="i14uz9bvv"/><path class="luptx_bzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calendar-clock" {...props}></Icon>
<style>
:global(.i14uz9bvv) {
  d: path("M9 15.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.luptx_bzl) {
  d: path("M12 14v1.25l1 1");
}

:global(.sa23nmb2h) {
  d: path("M3.5 5h17v15.5h-17ZM8 3v4m8-4v4M3.5 10h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
