<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e1b69obhg"/><path class="zxw2_6bqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:roundabout-exit-right" {...props}></Icon>
<style>
:global(.e1b69obhg) {
  d: path("M10 21.5v-7a5 5 0 0 0 5-5h4.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zxw2_6bqs) {
  d: path("m17.5 7.25l2.25 2.25l-2.25 2.25M10 14.5a5 5 0 1 1 4-8");
}

</style>
