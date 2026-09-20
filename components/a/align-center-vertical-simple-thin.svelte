<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gw9i1nb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:align-center-vertical-simple-thin" {...props}></Icon>
<style>
:global(.gw9i1nb-t) {
  fill: currentColor;
  d: path("M208 124h-36V48a12 12 0 0 0-12-12H96a12 12 0 0 0-12 12v76H48a4 4 0 0 0 0 8h36v76a12 12 0 0 0 12 12h64a12 12 0 0 0 12-12v-76h36a4 4 0 0 0 0-8m-44 84a4 4 0 0 1-4 4H96a4 4 0 0 1-4-4V48a4 4 0 0 1 4-4h64a4 4 0 0 1 4 4Z");
}

</style>
