<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpjn1jbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:market-share-sharp" {...props}></Icon>
<style>
:global(.lpjn1jbgs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 4.75A8.25 8.25 0 1 0 19.25 13H11Zm3.5 4.75l6-6m-4 0h4v4");
}

</style>
