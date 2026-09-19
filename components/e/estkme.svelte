<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v_5glj9pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:estkme" {...props}></Icon>
<style>
:global(.v_5glj9pk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.063 29.283l19.63-.06M8.486 5.5l23.277.028l7.752 7.628l-.113 29.344l-30.435-.327l.04-23.457l19.685.062");
}

</style>
