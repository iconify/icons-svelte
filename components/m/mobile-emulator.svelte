<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qusedmqjp"/><path class="th82f08iv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mobile-emulator" {...props}></Icon>
<style>
:global(.qusedmqjp) {
  d: path("M2 2.5h20V17H2ZM12 17v4m-4 0h8");
}

:global(.th82f08iv) {
  d: path("M8.75 5.25h6.5v9h-6.5Zm2 6.25h2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
