<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl1e5lbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:led-light-sharp" {...props}></Icon>
<style>
:global(.wl1e5lbod) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 15.5v-5a4.5 4.5 0 0 1 9 0v5Zm2.5 0v5.75m4-5.75v4.25m3.66-14.91l1.6-1.6m.13 4.2l2.77-1.15M17.5 10.5h3");
}

</style>
