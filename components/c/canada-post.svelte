<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="an5em3qwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:canada-post" {...props}></Icon>
<style>
:global(.an5em3qwf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.01 24.935L4.5 10.792l39 13.325L30.27 36.63l-25.77.579zm20.265-.461l-20.266.461m16.442 3.641l-20.267.461m16.443 3.641l-20.269.461");
}

</style>
