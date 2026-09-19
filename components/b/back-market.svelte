<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d4_jujj7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:back-market" {...props}></Icon>
<style>
:global(.d4_jujj7p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 7.857L26.357 24L42.5 40.143M21.643 7.857L5.5 24l16.143 16.143");
}

</style>
