<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ledy04cbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:closed-caption-outline-sharp" {...props}></Icon>
<style>
:global(.ledy04cbl) {
  fill: currentColor;
  d: path("M3 20V4h18v16zm2-2h14V6H5zm1-3h5v-2H9.5v.5h-2v-3h2v.5H11V9H6zm7 0h5v-2h-1.5v.5h-2v-3h2v.5H18V9h-5zm-8 3V6z");
}

</style>
