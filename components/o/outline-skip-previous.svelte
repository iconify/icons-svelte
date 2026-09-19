<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hef6o_beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-skip-previous" {...props}></Icon>
<style>
:global(.hef6o_beo) {
  fill: currentColor;
  d: path("M6 6h2v12H6zm3.5 6l8.5 6V6zm6.5 2.14L12.97 12L16 9.86z");
}

</style>
