<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t9biodbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:library-mobile" {...props}></Icon>
<style>
:global(.t9biodbvt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 39V9C23.699 9 24 29.696 24 39c0-9.304.301-30-19.5-30v30");
}

</style>
