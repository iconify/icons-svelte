<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mqd4l9b2e"/><path class="rxuyrcbli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:refill-jar" {...props}></Icon>
<style>
:global(.mqd4l9b2e) {
  d: path("M6.5 4.5V17A2.5 2.5 0 0 0 9 19.5h6a2.5 2.5 0 0 0 2.5-2.5V4.5m-12 0h13M12 8v7");
}

:global(.rxuyrcbli) {
  d: path("M9.5 12.5L12 15l2.5-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
