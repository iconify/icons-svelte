<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uqnf6ab0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:magnifying-glass-thin" {...props}></Icon>
<style>
:global(.uqnf6ab0v) {
  fill: currentColor;
  d: path("m226.83 221.17l-52.7-52.7a84.1 84.1 0 1 0-5.66 5.66l52.7 52.7a4 4 0 0 0 5.66-5.66M36 112a76 76 0 1 1 76 76a76.08 76.08 0 0 1-76-76");
}

</style>
