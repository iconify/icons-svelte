<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wzyxfibtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:circles-four-fill" {...props}></Icon>
<style>
:global(.wzyxfibtk) {
  fill: currentColor;
  d: path("M120 80a40 40 0 1 1-40-40a40 40 0 0 1 40 40m56 40a40 40 0 1 0-40-40a40 40 0 0 0 40 40m-96 16a40 40 0 1 0 40 40a40 40 0 0 0-40-40m96 0a40 40 0 1 0 40 40a40 40 0 0 0-40-40");
}

</style>
