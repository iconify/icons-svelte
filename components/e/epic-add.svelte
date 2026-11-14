<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zysghdcmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:epic-add" {...props}></Icon>
<style>
:global(.zysghdcmw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.898 15.241L17 10h-6.5L12 2.5l-9 11h6.5l-1.5 8l4.22-5.393M18 15v6m-3-3h6");
}

</style>
