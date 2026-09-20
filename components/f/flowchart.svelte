<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwep62bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:flowchart" {...props}></Icon>
<style>
:global(.nwep62bob) {
  fill: currentColor;
  d: path("M15 20v-2h-4v-5H9v2H2V9h7v2h2V6h4V4h7v6h-7V8h-2v8h2v-2h7v6z");
}

</style>
