<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fooxgwb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bravia-connect" {...props}></Icon>
<style>
:global(.fooxgwb1q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.166 42.5V24c0-6.811-5.521-12.333-12.333-12.333S5.5 17.189 5.5 24v18.5h37v-37H17.833v24.667H42.5m-24.667 0L5.5 42.5");
}

</style>
