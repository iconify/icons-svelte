<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llgiy1mtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eyewash-station" {...props}></Icon>
<style>
:global(.llgiy1mtr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10h16c0 5-3 7.5-8 7.5S3 15 3 10Zm8 7.5v4M8 10q0-5 1.5-7m4.5 7q0-5-1.5-7m6.5 7h2.5v5.5");
}

</style>
