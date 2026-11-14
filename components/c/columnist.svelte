<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wymraugdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:columnist" {...props}></Icon>
<style>
:global(.wymraugdm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 16c0-2.5 2.5-4.5 5.5-4.5s5.5 2 5.5 4.5m-11 3h19M16 19l.5-2.75l3.5-3.5l1.5 1.5l-3.5 3.5Z");
}

</style>
