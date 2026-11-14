<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwofb2b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:loose-leaf-tea" {...props}></Icon>
<style>
:global(.hwofb2b1e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19c0 4.5-4 7.5-9.5 7.5s-9.5-3-9.5-7.5m8 0C6 11.5 4.5 8 5 4.5c4 0 6 3.5 5.5 7.5m3 0c4.5-.5 6-4 5.5-7.5c-4 0-6 3.5-5.5 7.5");
}

</style>
