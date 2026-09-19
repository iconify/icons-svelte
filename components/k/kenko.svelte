<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v-6jjb8lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kenko" {...props}></Icon>
<style>
:global(.v-6jjb8lq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.001 32.5c0-9.389 7.61-17 16.999-17s16.999 7.611 16.999 17z");
}

</style>
