<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdvrtfb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wdvrtfb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-layout-border-right-border-cell-format-formatting-right" {...props}></Icon>
