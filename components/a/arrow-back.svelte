<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgs7_xe4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:arrow-back" {...props}></Icon>
<style>
:global(.sgs7_xe4x) {
  fill: currentColor;
  d: path("M20 11H7.83l5.59-5.59L12 4l-8 8l8 8l1.41-1.41L7.83 13H20z");
}

</style>
