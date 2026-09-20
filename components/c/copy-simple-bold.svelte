<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y17on7b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:copy-simple-bold" {...props}></Icon>
<style>
:global(.y17on7b9x) {
  fill: currentColor;
  d: path("M180 64H40a12 12 0 0 0-12 12v140a12 12 0 0 0 12 12h140a12 12 0 0 0 12-12V76a12 12 0 0 0-12-12m-12 140H52V88h116Zm60-164v140a12 12 0 0 1-24 0V52H76a12 12 0 0 1 0-24h140a12 12 0 0 1 12 12");
}

</style>
