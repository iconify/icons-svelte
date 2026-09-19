<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iv6z5ob1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mora" {...props}></Icon>
<style>
:global(.iv6z5ob1r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 24a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v15.5h-8.75V19a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v20.5H4.5V28h8.25a2 2 0 0 0 2-2V8.5h9v20a2 2 0 0 0 2 2h1.75a2 2 0 0 0 2-2v-15h9V31a2 2 0 0 0 2 2h3v6.5H37z");
}

</style>
