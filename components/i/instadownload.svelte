<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vzqebxbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:instadownload" {...props}></Icon>
<style>
:global(.vzqebxbob) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.105 33.644L9.099 18.638h8.649V5.5h12.714v13.138h8.648zM8.578 42.5h30.844v-3.647H8.578z");
}

</style>
