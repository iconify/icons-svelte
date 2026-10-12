<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyru41bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:closed-port-sharp" {...props}></Icon>
<style>
:global(.tyru41bxj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 11.75h10.5v7.5H6.75zm2.25 0V8a3 3 0 0 1 6 0v3.75m-4.5 2.75v2m3-2v2");
}

</style>
