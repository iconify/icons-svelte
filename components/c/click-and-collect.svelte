<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="znbdlsbag"/><path class="ak-1gcc1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:click-and-collect" {...props}></Icon>
<style>
:global(.ak-1gcc1i) {
  d: path("M14 12.75v8.75l2.25-2l1.5 2.5l1.75-1l-1.5-2.25l3-.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.znbdlsbag) {
  d: path("M11.2 19.5H2.5v-16h17v10.2M9 3.5V9m4-5.5v4.8");
}

</style>
