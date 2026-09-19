<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vdyr6fb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:block-blast-adventure-master" {...props}></Icon>
<style>
:global(.vdyr6fb8j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 24H24v16.5a2 2 0 0 0 2 2h14.5a2 2 0 0 0 2-2v-33a2 2 0 0 0-2-2h-33a2 2 0 0 0-2 2V22a2 2 0 0 0 2 2M24 24V5.5M42.5 24H24");
}

</style>
