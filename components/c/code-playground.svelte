<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mj-bw5btm"/><path class="z920z3b0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-playground" {...props}></Icon>
<style>
:global(.mj-bw5btm) {
  d: path("M11.7 19H2.5V2.5h14v8.9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z920z3b0r) {
  d: path("m8 8l-2.5 2.5L8 13m2.75-5l.99.99m-.021 3.041L10.75 13m3.75.5l7 4.25l-7 4.25Z");
}

</style>
