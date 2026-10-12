<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_tue2z5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:beaker-sharp" {...props}></Icon>
<style>
:global(.s_tue2z5h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75h14.5V14h-13V5.5ZM5.75 14h13v7.25h-13v-2.5Zm10-7.5h-2.5m2.5 3.5h-2.5");
}

</style>
