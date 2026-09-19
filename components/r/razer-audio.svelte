<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="drr1cc5qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:razer-audio" {...props}></Icon>
<style>
:global(.drr1cc5qz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.84 18.97v10.163m6.056-18.601v26.815M24.006 3.5v41m6.101-30.944v21.01m6.053-12.669v4.144");
}

</style>
