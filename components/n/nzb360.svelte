<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tugsx_3ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nzb360" {...props}></Icon>
<style>
:global(.tugsx_3ie) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.314 41.5v-35l19.209 9.767M40.686 6.5v35l-19.209-9.767");
}

</style>
