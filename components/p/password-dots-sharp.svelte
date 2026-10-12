<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u89ousbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:password-dots-sharp" {...props}></Icon>
<style>
:global(.u89ousbyc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8.25v5M3.33 9.5L7.67 12m0-2.5L3.33 12M12 8.25v5M9.83 9.5l4.34 2.5m0-2.5L9.83 12m8.67-3.75v5M16.33 9.5l4.34 2.5m0-2.5L16.33 12M3.25 17.5h17.5");
}

</style>
