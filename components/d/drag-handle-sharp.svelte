<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3dyevngv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:drag-handle-sharp" {...props}></Icon>
<style>
:global(.g3dyevngv) {
  fill: currentColor;
  d: path("M4 15v-2h16v2zm0-4V9h16v2z");
}

</style>
