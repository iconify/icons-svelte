<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdh1dnbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-two-split-left-focus-top-left-24-filled" {...props}></Icon>
<style>
:global(.wdh1dnbio) {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h11.5A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75zm1.5 11.5c0 .966.784 1.75 1.75 1.75h5V12H4.5zm8.25 1.75h5a1.75 1.75 0 0 0 1.75-1.75V6.25a1.75 1.75 0 0 0-1.75-1.75h-5z");
}

</style>
