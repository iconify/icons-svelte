<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytk243txw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:leaning-tower" {...props}></Icon>
<style>
:global(.ytk243txw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21.25h5q.75 0 .86-.74L16.7 8.24q.11-.74-.64-.74h-5q-.75 0-.86.74L8.36 20.51q-.11.74.64.74M11.81 7.5h3.5q.5 0 .57-.49l.42-2.77q.07-.49-.43-.49h-3.5q-.5 0-.57.49l-.42 2.77q-.07.49.43.49M8.78 17.75h6.5m-5.98-3.5h6.5m-5.97-3.5h6.5m-9.58 10.5h10.5");
}

</style>
