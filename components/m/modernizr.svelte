<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":123};
const content = `<path class="nw_094q0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:modernizr" {...props}></Icon>
<style>
:global(.nw_094q0b) {
  fill: var(--svg-color--d91b77, #d91b77);
  d: path("M0 122.88V81.92h40.96V40.96h40.96V0h40.96v122.88zM133.12 0C200.986 0 256 55.016 256 122.879H133.12z");
}

</style>
