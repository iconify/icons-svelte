<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfbdq0bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:bottom-sheets-sharp" {...props}></Icon>
<style>
:global(.pfbdq0bib) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-7.384h14V5H5z");
}

</style>
