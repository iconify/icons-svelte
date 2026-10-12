<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ontv6nb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:drill-sharp" {...props}></Icon>
<style>
:global(.ontv6nb5z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4.75h11.5v6.5h-5.75l.75 8.4l.111 1.106l-1.111-.006H6.75l-1.111.006l.111-1.106l.75-8.4H2.75v-6.5zm11.5 1H19v4.5h-2.5zM19 8h2.25M6.5 17.25H10");
}

</style>
