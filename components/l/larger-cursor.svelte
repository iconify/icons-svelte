<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0vxhyrzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:larger-cursor" {...props}></Icon>
<style>
:global(.w0vxhyrzz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.45 3.14l12.1 6.72q.7.39-.07.61l-4.71 1.31q-.77.22-1.08.96l-2.13 5.02q-.31.74-.53-.03L4.97 3.52q-.22-.77.48-.38m9.8 12.11l6 6m0-4v4h-4");
}

</style>
