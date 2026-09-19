<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lzexiwb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lowes" {...props}></Icon>
<style>
:global(.lzexiwb3s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.569 21.808v-2.594h-6.33L24 14.722l-10.239 4.492H7.446v2.594H4.5v11.47h39v-11.47z");
}

</style>
