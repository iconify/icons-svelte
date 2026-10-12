<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1yovomii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:procurement-sharp" {...props}></Icon>
<style>
:global(.i1yovomii) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.5h16.5v11.75H3.75zm0 4h16.5M12 2.75V6.5M9.75 4.25L12 6.5l2.25-2.25");
}

</style>
