<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ige05kbgf"/><path class="v48x_4kmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cause-bees" {...props}></Icon>
<style>
:global(.ige05kbgf) {
  d: path("M4.5 15.5a6.5 4.5 0 1 0 13 0a6.5 4.5 0 1 0-13 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v48x_4kmh) {
  d: path("M9.5 11C7 7.5 8 4 11 4s3.5 3.5 2 7.25m4.5 4.25h2M9.5 11v9m3.5-8.75v8.5");
}

</style>
