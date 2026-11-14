<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eq1hhjzmu"/><path class="qx-y3uuxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:businessman" {...props}></Icon>
<style>
:global(.eq1hhjzmu) {
  d: path("M9.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm0 16.75v-5H7v-3.75a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v3.75h-2.75v5");
}

:global(.qx-y3uuxm) {
  d: path("M10.25 9.75L12 12.5l1.75-2.75M12 12.5V15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
