<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gstcfgbtg"/><path class="m6yg0xv7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:exit-stamp" {...props}></Icon>
<style>
:global(.gstcfgbtg) {
  d: path("M11.6 21.5H3.5v-19h15v10.2");
}

:global(.m6yg0xv7o) {
  d: path("M7.5 9a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm.5 6.5h5.4M15 21l5.25-5.25m-4-.25h4.25v4.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
