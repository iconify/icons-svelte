<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey_mz0bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:hallway-sharp" {...props}></Icon>
<style>
:global(.ey_mz0bhf) {
  fill: currentColor;
  d: path("M4 21V5h4.885L12 1.885L15.116 5H20v16zm3.5-3.5h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zM10.139 5h3.723L12 3.139z");
}

</style>
