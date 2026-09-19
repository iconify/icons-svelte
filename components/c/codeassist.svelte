<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t56yhegds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:codeassist" {...props}></Icon>
<style>
:global(.t56yhegds) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.592 37.092L4.5 24l13.092-13.092m12.816 0L43.5 24L30.408 37.092");
}

</style>
