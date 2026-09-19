<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fe8fezwee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:okx" {...props}></Icon>
<style>
:global(.fe8fezwee) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 17.833H17.833v12.334h12.334zM42.5 30.167H30.167V42.5H42.5zm0-24.667H30.167v12.333H42.5zM17.833 30.167H5.5V42.5h12.333zm0-24.667H5.5v12.333h12.333z");
}

</style>
