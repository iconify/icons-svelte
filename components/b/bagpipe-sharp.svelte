<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glgjjwyon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bagpipe-sharp" {...props}></Icon>
<style>
:global(.glgjjwyon) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.63 17.39a6.25 4.5-20 1 0 11.74-4.28a6.25 4.5-20 1 0-11.74 4.28ZM7.75 11l4.5-7.75m-1.25 8l4.5-7.75M14.25 12l4.5-7.75M6 18.75l-2.25 2.5m1-9.5l-2-2.25");
}

</style>
