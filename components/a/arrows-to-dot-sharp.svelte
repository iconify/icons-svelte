<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk1nc1b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrows-to-dot-sharp" {...props}></Icon>
<style>
:global(.uk1nc1b-i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5v14m-8.25-7h5.5m11 0h-5.5M6.5 9.25L9.25 12L6.5 14.75m11-5.5L14.75 12l2.75 2.75");
}

</style>
