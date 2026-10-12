<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1mpp3buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:drywall-sharp" {...props}></Icon>
<style>
:global(.l1mpp3buu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h9.5v18.5h-9.5zm0 9.25h9.5m3.85 3h4.15l.11.59l.78 4.32l.11.59H14.5l.11-.59l.78-4.32l.11-.59zm.4-11H19v8.5h-2.5zm1.25 8.5V15");
}

</style>
