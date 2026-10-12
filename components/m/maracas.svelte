<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddu8v7bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:maracas" {...props}></Icon>
<style>
:global(.ddu8v7bmg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.6 3.81a3 3.75-10 1 0 1.3 7.38a3 3.75-10 1 0-1.3-7.38m10.8 0a3 3.75 10 1 1-1.3 7.38a3 3.75 10 1 1 1.3-7.38m-9.5 7.38l1.56 8.86m6.64-8.86l-1.56 8.86");
}

</style>
