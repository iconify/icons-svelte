<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o53ml77sg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-vertical-top" {...props}></Icon>
<style>
:global(.o53ml77sg) {
  fill: currentColor;
  d: path("M7.692 20.5V7.058h2.039V20.5zm6.577-6V7.058h2.039V14.5zM3 4.48v-1h18v1z");
}

</style>
