<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj2-kx-hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:first-aid-training" {...props}></Icon>
<style>
:global(.vj2-kx-hn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6Q9 3.75 3 4.5v14q6-.75 9 1.5q3-2.25 9-1.5v-14q-6-.75-9 1.5m0 0v14m4.5-10.5V13m-1.75-1.75h3.5");
}

</style>
