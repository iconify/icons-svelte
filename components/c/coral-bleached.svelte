<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zht82db6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coral-bleached" {...props}></Icon>
<style>
:global(.zht82db6j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.5v-13m0 12L6.5 10V5.5M12 12l5-5V4M2.5 20q2.375-2 4.75 0T12 20t4.75 0t4.75 0");
}

</style>
