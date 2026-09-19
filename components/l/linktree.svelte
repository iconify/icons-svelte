<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nl77v4m4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:linktree" {...props}></Icon>
<style>
:global(.nl77v4m4p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.126 20.084h31.748M12.775 8.859l22.45 22.45m-22.45 0l22.45-22.45M24 20.098V4.21m.002 25.942V43.5");
}

</style>
