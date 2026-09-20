<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ga95htbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:luminor-latvia" {...props}></Icon>
<style>
:global(.ga95htbrm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.2 4.5l5.55 5.55l-5.55 5.549l-5.55-5.55zm5.548 39H12.252V10.527h7.01v25.766h16.486z");
}

</style>
