<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w1zjl4b3s"/><path class="n5v89obeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:leotard" {...props}></Icon>
<style>
:global(.n5v89obeg) {
  d: path("M8.5 6.5q3.5 4.5 7 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w1zjl4b3s) {
  d: path("M8.5 2.5v4c0 1.5-3 2.5-3 5v2l5 8h3l5-8v-2c0-2.5-3-3.5-3-5v-4");
}

</style>
