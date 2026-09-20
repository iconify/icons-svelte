<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egm-z5ypv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:left-panel-close-outline-sharp" {...props}></Icon>
<style>
:global(.egm-z5ypv) {
  fill: currentColor;
  d: path("M15.596 15.173V8.827L12.404 12zM5 19h3V5H5zm4 0h10V5H9zm-1 0H5zm-4 1V4h16v16z");
}

</style>
