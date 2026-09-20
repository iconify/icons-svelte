<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns2gsxwyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:right-panel-open-sharp" {...props}></Icon>
<style>
:global(.ns2gsxwyc) {
  fill: currentColor;
  d: path("M11.596 15.173V8.827L8.404 12zM5 19h10V5H5zm-1 1V4h16v16z");
}

</style>
