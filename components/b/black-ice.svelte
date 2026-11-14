<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqwlqcbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:black-ice" {...props}></Icon>
<style>
:global(.uqwlqcbmz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5L9.5 4m8.227 8.688L14.5 4M12 8.5v6m6.5 1v6M16 17l5 3m-5 0l5-3");
}

</style>
