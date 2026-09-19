<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kvw0yxrau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:naptime" {...props}></Icon>
<style>
:global(.kvw0yxrau) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.474 9.641H43.5L24.474 38.359H43.5m-39-19.627h14.774L4.5 38.307h14.774");
}

</style>
