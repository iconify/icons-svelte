<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d4jkwuzsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:block-puzzle-jewel" {...props}></Icon>
<style>
:global(.d4jkwuzsr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5h12.333v12.333H24zm-12.333 0H24v12.333H11.667zM24 17.833h12.333v12.334H24zm0 12.334h12.333V42.5H24z");
}

</style>
