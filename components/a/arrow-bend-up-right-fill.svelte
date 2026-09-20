<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="j9s9n2dyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-bend-up-right-fill" {...props}></Icon>
<style>
:global(.j9s9n2dyy) {
  fill: currentColor;
  d: path("m229.66 109.66l-48 48A8 8 0 0 1 168 152v-40h-40a88.1 88.1 0 0 0-88 88a8 8 0 0 1-16 0A104.11 104.11 0 0 1 128 96h40V56a8 8 0 0 1 13.66-5.66l48 48a8 8 0 0 1 0 11.32");
}

</style>
