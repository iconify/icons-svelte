<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c2eiyt5kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:less-than-bold" {...props}></Icon>
<style>
:global(.c2eiyt5kk) {
  fill: currentColor;
  d: path("M210.84 205.13a12 12 0 0 1-16 5.71l-152-72a12 12 0 0 1 0-21.68l152-72a12 12 0 1 1 10.27 21.69L76 128l129.1 61.15a12 12 0 0 1 5.74 15.98");
}

</style>
