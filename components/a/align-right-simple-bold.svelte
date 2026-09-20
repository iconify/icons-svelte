<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tarnz9bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:align-right-simple-bold" {...props}></Icon>
<style>
:global(.tarnz9bdk) {
  fill: currentColor;
  d: path("M236 56v144a12 12 0 0 1-24 0V56a12 12 0 0 1 24 0m-40 40v64a20 20 0 0 1-20 20H32a20 20 0 0 1-20-20V96a20 20 0 0 1 20-20h144a20 20 0 0 1 20 20m-24 4H36v56h136Z");
}

</style>
