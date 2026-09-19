<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tdufhsbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mindvalley" {...props}></Icon>
<style>
:global(.tdufhsbjl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.5 32.555v-8.392a5.85 5.85 0 0 0-3.76-5.473c-3.116-1.193-8.035-2.679-14.24-3.246c2.828 6.165 8.259 12.648 18 17.111m3 0v-8.392a5.85 5.85 0 0 1 3.76-5.473c3.116-1.193 8.035-2.679 14.24-3.246c-2.828 6.165-8.259 12.648-18 17.111");
}

</style>
