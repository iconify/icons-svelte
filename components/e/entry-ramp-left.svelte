<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s2q29qqkn"/><path class="h3-8vi6zb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:entry-ramp-left" {...props}></Icon>
<style>
:global(.h3-8vi6zb) {
  d: path("M9.75 5.25L7 8l2.75 2.75");
}

:global(.s2q29qqkn) {
  d: path("M17 21.5v-19M17 17c0-6-5-9-10-9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
