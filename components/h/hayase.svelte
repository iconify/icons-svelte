<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mm7r6wbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hayase" {...props}></Icon>
<style>
:global(.mm7r6wbnv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 39.91V8.09l37 20.72v11.1L15.86 24.962v9.176zm37-17.02l-13.172-7.4L42.5 8.09z");
}

</style>
