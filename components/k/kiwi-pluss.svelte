<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nfympw37q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kiwi-pluss" {...props}></Icon>
<style>
:global(.nfympw37q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 14.25c0 10.772-8.728 19.5-19.5 19.5S4.5 25.022 4.5 14.25h8.717c0 5.955 4.828 10.783 10.783 10.783s10.783-4.827 10.783-10.783z");
}

</style>
