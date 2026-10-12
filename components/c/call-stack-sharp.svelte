<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-0bllbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:call-stack-sharp" {...props}></Icon>
<style>
:global(.h-0bllbem) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.75h13V7.5h-13zm0 7h13v4.5h-13zm0 6.75h13v4.75h-13zM4.5 20.75V4M2.75 5.75L4.5 4l1.75 1.75");
}

</style>
