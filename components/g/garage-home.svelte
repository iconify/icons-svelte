<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrydsb2py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:garage-home" {...props}></Icon>
<style>
:global(.hrydsb2py) {
  fill: currentColor;
  d: path("M4 21V9l8-6l8 6v12h-3V11H7v10zm5-2h6v-2H9zm0-4h6v-2H9z");
}

</style>
