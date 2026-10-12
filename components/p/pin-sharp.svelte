<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lae02zigs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pin-sharp" {...props}></Icon>
<style>
:global(.lae02zigs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 3.75h4.5v5.1l3.3 3.45l1.569 1.7H4.881l1.569-1.7l3.3-3.45ZM12 14v6.5");
}

</style>
