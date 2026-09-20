<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vccor0bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:in-home-mode-outline-sharp" {...props}></Icon>
<style>
:global(.vccor0bkt) {
  fill: currentColor;
  d: path("M5 19V9.452l-2.396 1.779l-.598-.787L12 3l10.02 7.439l-.604.792L12 4.25L6 8.716V18h2.673v1zm9.637 2l-3.533-3.538l.708-.714l2.825 2.825l5.675-5.65l.688.714z");
}

</style>
