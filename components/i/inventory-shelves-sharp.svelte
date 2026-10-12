<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocpnwz75r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:inventory-shelves-sharp" {...props}></Icon>
<style>
:global(.ocpnwz75r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.75v18.5m16-18.5v18.5M4 8h16M4 14h16M4 20h16M7 14v-3h5v3m0 6v-3h5v3");
}

</style>
