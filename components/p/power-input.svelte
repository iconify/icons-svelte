<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeeqhccob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:power-input" {...props}></Icon>
<style>
:global(.xeeqhccob) {
  fill: currentColor;
  d: path("M2 15v-2h5v2zm0-4V9h19v2zm7 4v-2h5v2zm7 0v-2h5v2z");
}

</style>
