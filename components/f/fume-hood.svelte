<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lobmfshzd"/><path class="bqp0lccvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fume-hood" {...props}></Icon>
<style>
:global(.bqp0lccvz) {
  d: path("M6.5 10.5h11V16h-11Zm-3 8.25h17M12 7.5v-5M9.75 4.75L12 2.5l2.25 2.25");
}

:global(.lobmfshzd) {
  d: path("M3.5 7.5h17v14h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
