<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhx-11oiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:action-call" {...props}></Icon>
<style>
:global(.qhx-11oiy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.5h18v10H3Zm-.728-3.424l16.629-3.534l.728 3.424L3 10.5Zm4.402-.935l2.684 3.008m2.207-4.048l2.684 3.008");
}

</style>
