<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azusqsqlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:grid-layout-side-outline-sharp" {...props}></Icon>
<style>
:global(.azusqsqlx) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h8.5V5H5zm14 0V5h-4.5v14z");
}

</style>
