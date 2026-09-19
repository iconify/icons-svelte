<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhtq1igtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-code-off" {...props}></Icon>
<style>
:global(.hhtq1igtk) {
  fill: currentColor;
  d: path("m19.17 12l-4.58-4.59L16 6l6 6l-3.59 3.59L17 14.17zM1.39 4.22l4.19 4.19L2 12l6 6l1.41-1.41L4.83 12L7 9.83l12.78 12.78l1.41-1.41L2.81 2.81z");
}

</style>
