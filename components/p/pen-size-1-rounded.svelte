<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omnxp7bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pen-size-1-rounded" {...props}></Icon>
<style>
:global(.omnxp7bqi) {
  fill: currentColor;
  d: path("M4.975 19.025Q4.75 18.8 4.75 18.5t.225-.525l13-13q.225-.225.525-.225t.525.225t.225.525t-.225.525l-13 13q-.225.225-.525.225t-.525-.225");
}

</style>
