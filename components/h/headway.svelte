<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="reojbdb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:headway" {...props}></Icon>
<style>
:global(.reojbdb_m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.2 10.838v26.325m15.113-26.325v26.325M16.375 17.175h14.937M16.2 32.288h15.113M4.5 24h39");
}

</style>
