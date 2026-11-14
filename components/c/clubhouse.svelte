<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hflmkbb8e"/><path class="iway7y6kf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:clubhouse" {...props}></Icon>
<style>
:global(.hflmkbb8e) {
  d: path("m2.5 12.5l9.5-5l9.5 5Zm1.5 0v9h16v-9m-8-5v-5m0 0L16.5 4L12 5.5Z");
}

:global(.iway7y6kf) {
  d: path("M10 21.5V17h4v4.5M6.5 16H8m8 0h1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
