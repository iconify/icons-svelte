<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="exxvlzbym"/><path class="m9fy4_0ed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:company-group" {...props}></Icon>
<style>
:global(.exxvlzbym) {
  d: path("M2.5 21V10h5.25V3h8.5v10h5.25v8Zm5.25-11v11m8.5-8v8");
}

:global(.m9fy4_0ed) {
  d: path("M10.5 21v-4h3v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
