<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beg_g1iqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:map-layer-buildings" {...props}></Icon>
<style>
:global(.beg_g1iqk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5H12v19H3.5ZM12 9h7.5a1 1 0 0 1 1 1v11.5H12m-5.75-15h3m-3 4h3m-3 4h3m5.5-1.5h3");
}

</style>
