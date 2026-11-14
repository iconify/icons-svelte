<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq7p7jb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:kayak-paddle" {...props}></Icon>
<style>
:global(.dq7p7jb0b) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.599 4.513l1.414-1.414q1.944-1.944 3.888 0t0 3.888l-1.414 1.414q-1.658 1.658-3.316.488l-7.282 7.282q1.17 1.658-.488 3.316l-1.414 1.414q-1.944 1.944-3.888 0t0-3.888l1.414-1.414q1.658-1.658 3.316-.488l7.282-7.282q-1.17-1.658.488-3.316");
}

</style>
