<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu3zzdbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lock-sharp" {...props}></Icon>
<style>
:global(.zu3zzdbsj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 10.75h14.5v10.5H4.75zm3 0V7.5a4.25 4.25 0 0 1 8.5 0v3.25m-4.25 4v2.5");
}

</style>
