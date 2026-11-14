<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hng2hsm0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:gnat" {...props}></Icon>
<style>
:global(.hng2hsm0v) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 6q0-3 3-3t3 3t-3 3t-3-3m18 3q0-3-3-3t-3 3t3 3t3-3M10 21q-3 0-3-3t3-3t3 3t-3 3");
}

</style>
