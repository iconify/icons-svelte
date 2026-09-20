<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":305};
const content = `<path class="wu0mdxd7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:payload" {...props}></Icon>
<style>
:global(.wu0mdxd7o) {
  d: path("M116.204 0L256 84.031v159.5l-105.265 60.896v-159.5L10.772 61.008zM105.49 171.121v124.463L0 232.13z");
}

</style>
