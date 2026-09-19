<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rlw1azpmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:heymelody" {...props}></Icon>
<style>
:global(.rlw1azpmg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.643v16.714A11.143 11.143 0 0 0 35.143 43.5h0V15.643A11.143 11.143 0 1 0 24 26.786");
}

</style>
